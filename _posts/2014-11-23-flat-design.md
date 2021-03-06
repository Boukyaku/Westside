---
layout: post
title: "了解扁平化设计"
description: "视觉 交互 原则 灵魂"
category: share
tags: [UX, UI, 设计]
imagefeature: default_bg1.jpg
comments: true
share: true
---

2013年，iOS 7的发布使得“扁平化”一词立刻火了起来，不论是Apple还是其他平台，不论设计师还是程序员，开口闭口都在谈论“扁平化”。时至今日，当初饱受争议的扁平化设计风格早已被各大平台各家厂商采用，它已经成为了最为前沿的设计风尚，Google不久前推出的Material Design亦为其全平台的扁平化设计规范。

殊不知，事实上扁平化设计是微软首先提出并运用的，并且扁平化设计的各种核心设计理念和规范也是微软率先提出的，然后苹果设备的使得这一设计思想广为用户所知。

# 那么，什么是扁平化？ #

先来看几个栗子：
 
## Microsoft ##

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_001.jpg">
	<figcaption>最纯粹的扁平化，核心理念的缔造者</figcaption>
</figure>

## Apple ##

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_002.jpg">
	<figcaption>华丽特效</figcaption>
</figure>

## Google ##

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_003.jpg">
	<figcaption>呃。。。。。。</figcaption>
</figure>

把三家的设计风格抽象出来的话就是酱紫：

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_004.jpg">
	<img src="{{ site.url }}/images/flatdesign/Image_005.jpg">
</figure>

# 设计的灵魂 #

## 内容 ##

更好地帮助用户理解内容并与之互动，但却不会分散用户对内容本身的注意力。

**充分利用整个屏幕。**天气应用是最好的例子：漂亮的天气图片充满全屏，呈现用户所在地当前天气情况这最重要的信息，同时也留出空间呈现了每个时段的气温数据。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_006.jpg">
</figure>

**尽量减少视觉修饰和拟物化设计的使用。**UI面板、渐变和阴影有时会让UI元素显得很厚重，致使抢了内容的风头。以内容为核心，让UI成为内容的支撑。

## 清晰 ##

文字应该易读，图标应该醒目，去除多余的修饰，突出重点。

**使用大量留白。**留白让重要内容和功能显得更加醒目。此外，留白可以传达一种平静和安宁的视觉感受，它可以使一个应用看起来更加聚焦和高效。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_007.jpg">
</figure>

**让颜色简化UI。**一个主题色——比如在记事本中使用的黄色——让重要区域更加醒目并巧妙地表示交互性。这同时也给了一个应用一个统一的视觉主题。内置应用使用家族化的系统颜色，无论在深 色和浅色背景上看起来都干净，纯粹。
 
<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_008.jpg">
</figure>

## 深度 ##

视觉的层次和生动的交互动作赋予UI新的活力，帮助用户更好理解UI的操作并感到惊喜。

**在不同的层级上展现内容，**用以表达分组和位置，并帮助用户了解在屏幕上的对象之间的关系。

日历有较深的层级，当他们在翻阅年、月、日的时候，以及增强的交互动画给用户一种层级纵深感（循序切换的层次，从年到月到日）。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_009.gif">
</figure> 

# 高效 #

## 层级 ##

精简交互步骤，用户用最少的步骤就完成任务。

**交互步骤和层级结构是相互关联的。**从图中可以看出来， 这个是一个树形结构，在树形结构中，链接的层数被称为深度（z轴），最底层页面包含的页面总数被称为链接的广度（x轴）。纵向（y轴）很多情况下都只有一层，放的多都是一些消息提醒和快捷方式。
 
<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_010.jpg">
	<figcaption>一个典型的树形结构</figcaption>
</figure>

**广度：**最底层页面就是他的首页，包含的页面综述非常丰富，可以看到从广度来讲覆盖面是非常大的。
 
<figure>
	<img src="{{ site.url }}/images/rwd_1.jpg">
</figure>

**深度：**从鞋包配饰－到女鞋－到单鞋－到单鞋的各种类型

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_012.jpg">
	<figcaption>买买买＼( ^▽^ )／</figcaption>
</figure>

**可以看出，Web网页更注重深广度的平衡。**

但是如果直接把web上的结构搬到手机上是行不通的。 由于手机设备的限制，淘宝的手机主界面的广度大大减弱，信息深度更为明显。

PC上我们可以用面包屑路径或者各种导航清晰的表现出层级结构，让用户不在复杂的层级机构中迷路。

但是在移动设备上显示区域有限，没有足够的地方用来放这样的路径，更多的时候我们只能用Back。
 
## 并列 ##

将并列的信息显示在同一个界面中，减少页面的跳转。

在此之前什么天气啊邮件啊，都得打开具体的应用才能看到（提插件的哪儿凉快哪儿呆着去），而Windows 8在同一个界面中就能展示出这些信息（当然这个还有很大的改进空间）。
 
<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_013.jpg">
</figure>

## 快捷方式 ##

层级结构减少，用户不用再一层一层地到设置里面去按，提高效率的同时也使结构变的清晰。

以iOS 7为例，在任意界面只要向上滑动都能从底部呼出一个快捷菜单。

设置Wi-Fi和手电筒神马的可以直接从这个菜单里面操作。
 
<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_014.gif">
</figure>

## 关键信息 ##

在“选择影院”这个界面中除了显示出影院名称，还显示出了“最低价”xx元起， 以及余下场次，还有是否可以购票这些关键信息，这里结合场景考虑，用户既然点了“选座购买”那用户的购买欲应该是很强的，这样在这里显示出的关键信息，就能使得用户在选择影院的同时也能看到最低价，不用在挨个影院点进去看了，也能加快购买效率。
 
<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_015.jpg">
	<figcaption>豆瓣购票</figcaption>
</figure>

## 手势 ##

iOS 7以后关闭后台程序，只需要用手指轻轻往上一滑走就关闭了，而iOS 6则是长按出现删除按钮后再挨个关闭。

当然这里要引起注意的是，滑动手势，显然没有点按的提示来的明显， 所以滑动手势这类型的操作一定要设计的自然，否则用户找不到点哪里不知道怎么操作就会产生挫败感而放弃使用。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_016.jpg">
</figure>

## 高效 ##

**层级结构减少，交互步骤必然减少，无疑让用户的使用效率得到了提高。**

移动端由于设备本身的限制，没有足够的空间来展示路径，如果没有清晰的层级关系，这可能就意味着用户很有可能迷失方向，甚至要进入深层次的信息才能找到他们想要的，这时更应该做的是减少信息的深度。
 
# 准确 #

如果你的功能不能让用户一眼就看明白，还需要解释的话，那么你这个功能就做失败了。

**减少按钮和选项，让使用更简洁。 **

更加直观的表达方式，让用户能更准确的使用体验，不用在去为这里 要怎么操作而苦恼。

例如摇一摇，用户的本能反映，不需要任何解释，连小孩都知道，只要拿着手机晃动就能实现这个功能。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_017.jpg">
</figure>

# 有序 #

分类无助于降低产品使用的难度，但是可以帮助用户认知产品和周边的世界。

**整理。**把互联网里大量的信息整理的有序清晰，让用户能根据你整理的清晰分类快速找到自己需要的东西。

通过整理，我们能找到事物的本质，发现全新的观点，看到一些深藏于表面的事物。通过整理，我们视野里问题会变得越来越清晰，并且获得许多新发现。
 
<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_018.jpg">
	<figcaption><a href="http://book.douban.com/subject/3682204/" data-toggle="tooltip" title="佐藤可士和的超整理术">佐藤可士和的超整理术</a> 图例</figcaption>
</figure>

减少过度繁杂元素的交互界面设计，让信息更直观的展示。

干净整洁有序，永远比杂乱无章跟让人赏心悦目，及时在信息量很大的情况下，在有序的环境里面找起来也会比较方便快捷。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_019.jpg">
</figure>

# 交互 #

## 响应 ##

扁平化很大程度是出于信息化的诉求。

**响应式设计**

随着各种像素密度的联网设备的普及，交互界面变得更需要强调适应其变化，响应式设计也就孕育而出。虽然响应式设计并没有风格上的固定的要求，但扁平的交互界面显然比其它样式要更容易处理。

<figure>
	<img src="{{ site.url }}/images/rwd_4.gif">
</figure>

## 沉浸 ##

在用户会花较长时间并集中绝大部分注意力去与产品进行交互时，可以使用沉浸式设计。沉浸式设计的意图在于尽可能排除用户关注内容之外的所有干扰，让用户能够顺利 地集中注意力去执行其预期的行为，并且可能会利用用户高度集中的注意力来引导其产生某些情感与体验。

Immersion在《设计的法则》中提到了，其中对Immersion的解释就是使用的心流理论flow(心流)，关于心流可参照经典著作《Flow:the psychology of optimal experience》。

沉浸就是**让人专注在当前的目标（由设计者营造）情境下感到愉悦和满足，而忘记真实世界的情境。**

心流理论的基础观点非常简单，但是非常有力地解释了人们废寝忘食地投入一件事情的状态。参见下图：

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_021.jpg">
</figure>

心流理论的核心就是说人在技能与挑战匹时才能达到心流状态。我们可以试想以下，什么游戏会让你投入地废寝忘食，肯定是那种有一定挑战，并且我们自己根据已知的条件判断自己是有能力应对此挑战的。如果太难，估计在尝试几次后就放弃了，并且人会越来越焦虑，而感受不到本身过程中应有的乐趣和满足。而如果太简单，我们就会感觉到无聊，也迅速放弃了当时的体验。心流体验是人的最优体验，就正是它是在我们当前面临的挑战和本身能力相匹配的状态下，我们能达到前述的沉浸在当前情境中，而忘记真实世界的状态，所以经常会出现**我们认为只不过玩了几局DOTA，而已经从中午到天黑了。**因为心流能改变人对真实时间的感知能力。（当然心流状态并不限于游戏领域，任何可以达到忘我，忘乎时间的状态都可能是心流状态。)

沉浸式体验的内容：

沉浸式体验往往即包括人的感官体验，又包括人的认知体验。

- 感官体验：例如游乐场，迪斯尼主题乐园，很多活动对人有一定挑战，但是主要是利用人的感官体验，让人从而感觉到爽或者刺激。但是利用感官刺激达到心流状态，很难维持长久。
- 认知体验：例如下棋，扫雷等等策略游戏，又如教学这些活动对人的技能与挑战匹配主要利用人的认知经验。

而事实证明，即包含丰富的感官经验，又包含丰富的认知体验的活动才能创造最令人投入的心流。

游戏当然是使用最广泛地方，因为游戏中最容易也最需要使人达到心流状态。而在现实生活中的使用也是非常广泛。例如KTV的环境与灯光营造出让人分不清是白天或黑夜的感觉，商场的环境要注重打造的是让人沉浸在忘我的购物中流连忘返而忘记时间。而迪斯尼乐园等主题乐园，甚至赌场就更加擅长使用沉浸式设计来虏获顾客长时间驻足了。

归纳沉浸式（心流）的特点如下：

**条件因素**

- 用户在体验过程有非常明确的目标（例如购买的目的，或是放松自我，纯粹的玩），也就是不能让人感觉不知所措，不知道该干嘛，就如游戏设计，对于单局游戏体验的目标设计要非常明确，是得高分，通关，抑或其他。）
- 对用户的交互行为有即时的反馈（让人感觉任何互动都有回应，并且是在可接受范围时间内的响应，尤其在游戏设计当中非常重要，在用户动作与响应之间的时间间隔设计）
- 能力与挑战匹配（需要给予用户一些困难，例如更强大的怪物，但是同时也需要着手通过关卡设计来提高用户的能力）

**体验因素**

- 用户行动与知觉的融合
- 注意力集中（用户的专注力非常高，是心流状态中非常重要的特点，）
- 用户对活动有绝对的主控感

**结果因素**

- 失去自我意识
- 对时间的错觉（也就是对时间认知发生了扭曲，在体验中将时间认知拉长，或将时间认知缩短，例如投入玩游戏时典型的时间认知缩短。）
- 体验即目标（实际上在真正达到心流状态后一开始我们所说的条件，也就是引起心流的明确目标会变成体验本身，就比如我们在玩游戏最爽时并不是击败怪物的瞬间，而是游戏不断创造一个新的挑战，而自己通过提升能力去克服挑战这种感觉。）

何为沉浸式设计？

依据之前的叙述，那么我们可以将为了沉浸式（心流）而进行的设计可以称之为沉浸式设计（为心流而设计）。

常见沉浸式设计法则：

- 叙事性设计（讲故事）storytelling，利用情境，沉浸，角色，气氛，情节，节奏的设计来让观众融入故事本身当中来。这也是非常基础的设计手法之一。关于叙事性设计我读到的最好叙述在赵江洪老师写的《设计心理学》里面。
- 最省力法则：降低人们在达成目标时的认知阻力（达成目标的脑力活动总量）和运动阻力（达成目标的体力活动总量）就是最省力法则。

在用户界面上，沉浸式设计就是把用来导航的各种界面操作空间隐藏在以程序内容为主的情景中，通过相对“隐形”的界面来达到把用户可视范围最大化地用到内容本身上。

# 色彩 #

## 选色 ##

色彩的原则：鲜艳而不刺眼（什么意思啊？）

## 颜色 ##

色彩有助于增进沟通

**颜色会用于表征交互，传递活性以及提供视觉连续性。**使用那些看起来更具个性的、纯粹、干净的颜色，并辅以或亮或暗的背景组合。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_022.jpg">
</figure>

> 如果你要创建多样的自定义颜色，要确保它们能够和谐共存。
> 
> 注意在不同情境下的颜色对比。色彩可以向用户传达信息，但不一定会以你希望的方 式。 
> 
> 大多数情况下，不能让颜色喧宾夺主，让用户分心。

## 配色 ##

确定背景色：非白色，暖色、冷色、图片。

<figure class="third">
	<img src="{{ site.url }}/images/flatdesign/Image_023.jpg">
	<img src="{{ site.url }}/images/flatdesign/Image_024.jpg">
	<img src="{{ site.url }}/images/flatdesign/Image_025.jpg">
</figure>

**暖色**

不要过多使用，容易亮瞎观众眼球，而且看久了眼睛会有视色错觉现象（就是跟残像一个意思，嗯，差不多）

<figure class="half">
	<img src="{{ site.url }}/images/flatdesign/Image_023.jpg">
	<img src="{{ site.url }}/images/flatdesign/Image_027.jpg">
</figure>
 
**冷色**

比较常见使用的时候注意图元素颜色的兼容，例如跟图表、色块颜色的对比一定要够大。
 
<figure class="half">
	<img src="{{ site.url }}/images/flatdesign/Image_024.jpg">
	<img src="{{ site.url }}/images/flatdesign/Image_029.jpg">
</figure>

**图片**

图片简单的可以直接使用，复杂的建议先做模糊、调暗处理或者加色块，遵循不刺眼、不影响信息的原则。

<figure class="half">
	<img src="{{ site.url }}/images/flatdesign/Image_030.jpg">
	<img src="{{ site.url }}/images/flatdesign/Image_031.jpg">
</figure>

## 色系 ##

### 多色系 ###

确定主色，再选4到5种颜色做辅色，来做色块的颜色。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_032.jpg">
</figure>

### 单色系 ###

以主色为基础，改变颜色的饱和度和亮度。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_033.jpg">
</figure>

# 色块 #

在很多时候扁平化的视觉设计中，是很少有线条出现的，更多是用色块来表现各种关系。

也有一些是走复古风，同色系，和低饱和度⋯⋯

重要的是各种调调放在一起看起来要**和谐**

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_034.gif">
</figure>

## 形状 ##

结构尽量简单

**建议简单、规则的图形**避免复杂不规则的图形

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_035.jpg">
</figure>

## 大小 ##

形状的大小也有讲究

**大小取决于内容，**一定要留有适量空白距离

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_036.jpg">
	<figcaption>留有一点空间</figcaption>
</figure>

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_037.jpg">
	<figcaption>喘息的空间都没有了</figcaption>
</figure>

# 文字 #

## 排版 ##

在扁平化设计中采用的都是极简的元素，所以，排版就显的尤为重要。

**字体，特别是中文，**又是大家觉得很头痛的一个地方，同样的排版同样的背景，很多时候放英文看起来很舒服，那是因为英文的机构简洁而且可塑性很强，但是中文放上去 就没有那么好的效果。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_038.jpg">
</figure>

## 字体 ##

通常情况下，应用中整体应该使用尽量少的字体。

多种字体的混杂会使你的应用看上去支离破碎和草率。相反，使用尽可能少的字体和少数样式。
 
<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_039.jpg">
</figure>
 
## 选字原则 ##

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_040.jpg">
</figure> 

## 字体 ##

推荐使用的中英文字体

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_041.jpg">
</figure> 

## 字体颜色 ##

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_042.jpg">
</figure> 

# 图标 # 

## 提炼 ##

图标的提炼是一门技术
 
**图标不是随意用**

图标帮助用户理解内容，让用户可以在图标就了解内在的方向，并且加深用户的印象。

**图标与标题同等重要**

在有图标的情况下，图标与标题同等重要，甚至比标题更需要动脑。
 
举个栗子：

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_043.jpg">
	<figcaption>是不是看不懂英文都知道是广州卫视新闻频道？</figcaption>
</figure> 

用户常常会在看到图标的时候便建立起第一印象，并以此评判应用的品质、作用以及可靠性。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_044.jpg">
</figure>


> 应用图标是整个应用品牌的重要组成部分。将图标设计当成一个讲述应用背后的故事，以及与用户建立情感连接的机会。
> 
> 最好的应用图标是独特的，整洁的，打动人心的，让人印象深刻的。
> 
> 一个好的应用图标应该在不同的背景以及不同的规格下都同样美观。为了丰富大尺寸图标的质感而添加的细节有可能让图标在小尺寸时变得不清晰。

# 图片 #

一张好看的图片能吸引大家注意力和点击的欲望。
	 
<figure class="half">
	<img src="{{ site.url }}/images/flatdesign/Image_045.jpg">
	<img src="{{ site.url }}/images/flatdesign/Image_046.jpg">
	<figcaption>整页</figcaption>
</figure>
 	 
<figure class="half">
	<img src="{{ site.url }}/images/flatdesign/Image_047.jpg">
	<img src="{{ site.url }}/images/flatdesign/Image_048.jpg">
	<figcaption>大面积</figcaption>
</figure>

<figure class="half">
	<img src="{{ site.url }}/images/flatdesign/Image_049.jpg">
	<img src="{{ site.url }}/images/flatdesign/Image_050.jpg">
	<figcaption>区块</figcaption>
</figure>

# 动画 #

使得设计的体验更具吸引力、更具动态性。

<figure>
	<img src="{{ site.url }}/images/flatdesign/Image_051.gif">
</figure>

适当的动画可以：

- 传达状态和提供反馈
- 增强直接操作的感觉
- 帮助人们可视化他们的操作结果

# 思考 #

有效的整理信息，减少层级结构，功能表达方式直白等等都是使交互扁平化的多种手段。

交互的扁平化设计，其实是一个概念，是一种内在的设计思想，目的是能在环境需求多种变化的情况下，依旧能提高用户体验的一种方法。

追求“扁平化”是我们的设计目标。不管是从视觉上，还是从交互上都应该根据产品的实际情况／场景以及用户来具体分析，才能达到真正扁平的目标从而提供优质的用户体验。
 
### 参考资料： ###


- [iOS Human Interface Guidelines](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/index.html#//apple_ref/doc/uid/TP40006556-CH66-SW1)

- [@嘉文钱](http://weibo.com/425671110)

- joy [做好扁平化设计－交互篇](http://cdc.tencent.com/?p=7913),[做好扁平化设计－视觉篇](http://cdc.tencent.com/?p=7844)

- 知乎 [什么是沉浸式设计？它有什么具体特点？](http://www.zhihu.com/question/19604582/answer/19537511)
