---
layout: post
title: "响应式设计"
description: "响应式Web设计与APP开发"
category: share
tags: [UX, 设计]
imagefeature: default_bg1.jpg
comments: true
share: true
---

 <figure>
	<img src="https://y6cvag.tuk.livefilestore.com/y2pgJ5tIA6D6g_bUic7CX2duTI-MsaQV4wWLUAre1CiW03QoeL0N3q6vyZwmpdl3hSxg_B6jm8msI6gTN_scV_BwF7xGAdFHpH1_KaAHgQPDpcPoLmszxKtXmXz6ueGBWGZkQS6Qa-fGvnZXlPSHS1HcA/rwd_1.jpg?psid=1">
	<figcaption>这是一个喜闻乐见的淘宝主页</figcaption>
</figure>

大家都喜欢逛淘宝吧，看见喜欢的就各种“买买买”，买完后“剁手”，“双十一”、“双十二”时尤甚。用户在PC浏览器上打开淘宝主页，可以直接搜索，也可以通过主页上的层及目录一层层查找自己需要的商品，整个淘宝主页的设计已然高效有序，但如果用手机浏览器访问淘宝主页，绝大多数手机浏览器都会跳转到淘宝网手机版（http://m.taobao.com），其设计与PC版页面大不相同。

淘宝的PC主页更注重深广度的平衡，但是直接把PC上的结构搬到手机上是行不通的。由于手机设备的限制，淘宝的手机主界面的广度大大减弱，信息深度更为明显。PC上我们可以用面包屑路径或者各种导航清晰的表现出层级结构，让用户不在复杂的层级机构中迷路。但是在移动设备上显示区域有限，没有足够的地方用来放这样的路径，更多的时候我们只能用Back。

现如今手机和平板等移动设备快速普及，用户花在移动端的时间越来越多，移动互联网的数据流量不久将超越PC端的流量，因此PC互联网向移动端迁移势不可挡。现如今用户手机访问网页很多都是用在那些没有客户端的网站（某些平台上客户端做的还不如网页好的就不吐槽了）和点击链接上，如果这个网页没有针对移动设备进行优化，那么页面体积大、请求多、体验差、兼容性差，层层阻碍最终导致用户体验恶化。试想：用手机访问“电脑版”淘宝主页，那画面太美我不敢看。。。

因为屏幕大小的改变, 用户体验也得跟着变, 用户希望在手机上浏览网页就跟在电脑上一样轻松。但是大家发觉没有，http://www.taobao.com与http://m.taobao.com是两个网页、是两套不同的代码、两个不同的设计，那么问题就来了：为什么一定要为每个用户群各自打造一套设计和开发方案？

看一看QQ空间：

- PC – http://qzone.com
- Mobile – http://m.qzone.com
- 响应式：PC & Mobile – http://qzone.com 无需跳转

无论用户正在使用PC还是平板或者手机，页面都应该能够自动切换分辨率、图片尺寸及相关脚本功能等，以适应不同设备；换句话说，页面应该有能力去自动响应用户的设备环境。响应式Web设计就是一个网站能够兼容多个终端——而不是为每个终端做一个特定的版本。这样，我们就可以不必为不断到来的新设备做专门的版本设计和开发了。

响应式设计应该做到根据不同设备环境自动响应及调整。当然响应式设计不仅仅是关于屏幕分辨率自适应以及自动缩放的图片等等，它更是一种对于设计的全新思维模式。

啰嗦了这么多终于来到重点。响应式Web设计(Responsive Web Design)的理念是：集中创建页面的图片排版大小，可以智能地根据用户行为以及使用的设备环境（系统平台、屏幕尺寸、屏幕定向等）进行相对应的布局。
 
 <figure>
	<img src="https://y6cvag.tuk.livefilestore.com/y2pe4L-DYUVtPdxUzxMtJgmth5U_wHSZiQycOSStTSWdP5ls6yXnZTo3klfQJTP6hN-dp5qs2ZpxQ1Ygty-doneSRNJr2ZfCUKmumf_9NG18vPFih7nN6jIyUrJQ1fsD7JNBH53Ip7X7NWZDcaeqYCTtg/rwd_2.jpg?psid=1">
</figure>

响应式设计的一个发展契机是HTML5的普及。HTML5带来了移动互联网的革命，大量的语法更新，提高了运行效率，并且它有着得天独厚的跨平台优势，使得基于HTML5的移动开发越来越广泛，这更促进了Web APP和Hybrid APP开发的兴起。

千万不要认为响应式设计仅仅针对于Web哦，你有没有注意过：同样版本的一个应用在你的iPhone和iPad里所展示的内容是有所不同的，甚至应用横竖屏切换后的界面也是响应式设计的体现。
说到APP开发，我们先来看看三大APP开发类型：

1.	Native APP：Native Code编程，代码编译之后以2进制或者字节码的形式运行在OS上，直接调用OS的Device API；
2.	Web APP：以HTML5+JS+CSS等WEB技术编程，代码运行在浏览器中，通过浏览器来调用Device API；
3.	Hybrid APP：部分代码以Web技术编程，部分代码由某些Native Container承担（例如PhonGAP插件，BAE插件），其目的是在HTML5尚未完全支持Device API和Network API的目前阶段，承担这部分职责。
 
 <figure>
	<img src="https://y6cvag.tuk.livefilestore.com/y2pqAJKZ0YFo7J6N4Ay4fqSo00kY88gJ66XI71eShG-PG2Re2RnJ8gbkN8LG-INYvOwiFlQ3WDxgdQu56CLHs4KVQFRFAPDv68TnaLsVpnx8PuICQxjUOs-G7dqsbMUTv_2rxJkJGSV-er0KYe6ejUUhw/rwd_3.jpg?psid=1">
</figure>

开发Native APP需要学习Objective-C、Java等语言，学习成本高，跨平台难，迭代慢且需要大量系统资源，开发成本高；Web APP门槛低，极易上手，迭代快，跨平台且开发成本极低；Hybrid APP介于前两者之间，兼具两者优势，便于移植开发，成本低于Native APP。

响应式设计之于APP同样关系到布局以及图片等等问题，至于哪种开发模式更合适不在我们讨论的范畴，我们继续来谈设计。

那么，我们如何实现响应式设计？

从两个方面来考虑：

## 1.	设计方面：

响应式设计首先面对的就是对不同设备不同分辨率的兼容，这关系到布局以及图片的自适应能力。
 
 <figure>
	<img src="https://y6cvag.tuk.livefilestore.com/y2pF88bIFyjx4iAeJi22_qaDh4gqSmBZWEIlSs4uigqfyMldsCvXyi9B8p9oFwQRWsV119DIXBiXvC868E62hjq5UD9AP5XHe4kXriYEngFmL6fpg7BYQd1Y7ogCCdM0R7Tsq1nkHNmCzqt8P-qJstdqQ/rwd_4.gif?psid=1">
</figure>

不同的设备都有各自的屏幕分辨率、清晰度以及屏幕定向方式，不断被研发着的各种新设备也将带来新的屏幕尺寸规格。有些设备基于横屏（比如PC），有些是竖屏（比如手机平板），甚至还有正方形，用户还可以通过转动设备来任意切换屏幕的定向方式。定向不同时的界面空间是不同的，这直接决定了控件的放置方式。比方说在横屏时显示10列菜单，竖屏时要么缩放菜单尺寸，要么自动显示5列——因为空间不够。
 
 <figure>
	<img src="https://y6cvag.tuk.livefilestore.com/y2pF6lR0jvwusxhaLS8TsyNdFCvzNQ39Ud_o3faWS4oN_KJAvjzCi0ryQU_lmIWHIfajp_vXfm61t1BiJKN-2fsTXOGU-4VTJeBvO43rDvXePAbcWH1L_PVGvcjXTn5jXqE6Q7ESeukO0vEyYFHdjp1RQ/rwd_5.jpg?psid=1">
</figure>

响应式设计的一大特点是不同平台共用一套代码，这就意味着在所有分辨率上使用的控件和界面元素都是基本相同的，因此，在无法改变控件的情况下就可以通过缩放控件尺寸或者调整不同元素的间距等方法来达到响应式设计的目的。
 
 <figure>
	<img src="https://y6cvag.tuk.livefilestore.com/y2pdfMyX6Wx1HdEoeERAPZjOWSaEgh7JuSBRwEbugUuPdedoI3-uQKz37TAC4gX6bQ-iRuC2eG4FB6bI4hHImqdbeMzHFxczI6gzpvK2TvskIZBj4rCLedWJFZdtWjkpciVafib3zX-rt_5NN5Y8fCG5A/rwd_6.jpg?psid=1">
</figure>

如果改变界面元素，那么基本设计原则也务必保持一致。在PC上由于空间大，设计比较随心所欲，但到了小空间上，直接照搬PC的风格有可能显得不伦不类，反之亦然。看下图，虽然Mac上的button到了移动设备上变为了list，但整体风格并未改变，看一眼就知道是同一个网站。
 
 <figure>
	<img src="https://y6cvag.tuk.livefilestore.com/y2pnH0HY4oadF_1YVumlCqfgVUOaRssoFyKStwPLiTaPUu7xvbHjT8jXKETdA0csuJJhCl1M0d_YQenCmqhTH9G1kOnw_qqhqpTu3UB6X-uibLE71cKqTKTAMMokr5qEKz0A06sfxsh0Npd-rxXJSwC0Q/rwd_7.jpg?psid=1">
</figure>

当然，调整的不仅仅是界面元素，字号也需要自适应。许多OS已经可自动调整字号，设计时应该考虑到OS自适应缩放对布局的影响。
 
 <figure>
	<img src="https://y6cvag.tuk.livefilestore.com/y2pZ6jCmA8ehcBOqVLAjV58066jlHkwVPK5b_wYhnFdKL_tYpWtalpUkTNBs8ftZKwg92UptRbjn-5Z4lNBXr5qnmJYa0lW_n20W8RjDFOwLnRjh8BNhOFPzfFyr6kd9a498j00MFyb7u46-75Uad5dUg/rwd_8.jpg?psid=1">
</figure>

在响应式设计里常提到的“弹性布局(flexible layout)”，“弹性”即尺寸、字号以及图片都可以自动调整。

带宽始终是移动端的硬伤，如果我们只是页面布局做了响应式处理，在我们用移动端访问时，请求的图片还是PC上的大图，文件体积大，消耗流量多，请求延时长，因此导致的问题也是不可估量的。那么我们就得把图片也处理成响应式的根据终端类型尺寸分辨率来适配出合理的图形。

在iOS里的切图有@1x、@2x、@3x三种尺寸，Android等其他OS里也有类似的切图渲染方案，这是为适应不同分辨率而设计的。

图片的响应式，不仅要同比的缩放图片，还要在小设备上降低图片自身的分辨率。很多OS都支持自动缩放图片了，不过有时自带的缩放功能可能不能达到需求的效果，这时就要通过代码来实现。
 
 <figure>
	<img src="https://y6cvag.tuk.livefilestore.com/y2py2QvQN_Rpj-0z1nkDsYIfcQDtx_uG8sCLNBbvMHyL5obo3pCDl7IEmFKn3FdaEULWy_MLGdKyH0oJkAqqud6m5NBREW1Cdv2vaNT02g_ujpL9h1xkVyS59nep7ERCLr_ju3LMzkWUlqNiQqrBFqS8g/rwd_9.jpg?psid=1">
</figure>

触屏设备已经成为了主流，相比于传统的基于鼠标指针的互动，触屏技术显然带来了截然不同的交互方式与相应的设计规范，两者又有各自所适用的领域。比如，触屏设备无法反映CSS定义的`hover`行为及相应的样式，因为它没有鼠标指针的概念，手指点击就是`click`行为。如果是响应式的网页，不要让任何功能依赖于对`hover`状态的触发。

设计师还应该负责任地考虑一下，他的设计对开发难度的影响，因为响应式设计势必会增加代码量。

## 2.	开发方面：

前端开发要比设计师考虑更多技术问题，比如兼容性，比如不同平台的渲染，在处理完这些令人头大的问题后就可以投入到主体开发中去了。

说到响应式布局，就不得不提起CSS3中的Media Query，它可是个好东西，易用、强大、快捷……Media Query是制作响应式布局的利器，使用这个工具，可以非常方便快捷的制造出各种丰富的实用性强的界面。

更多关于开发的内容可以看看[《响应式网页设计》](http://isux.tencent.com/responsive-web-design.html)和[《谈响应式web设计代码实现》](http://isux.tencent.com/code-of-response-web-design.html)这两篇文章，在此就不赘述。

## 思考

随着各种像素密度的联网设备的普及，交互界面变得更需要强调适应其变化，响应式设计也就孕育而出。它可以灵活地面对各种新兴设备不同的分辨率，便捷的解决显示适配问题，当然，响应式设计也存在着代码冗余导致效率低下等弊端，这些都值得设计和开发人员深思。
响应式不只是技术的实现，它更是一种对于设计的全新思维模式。

 <p style="text-align: right;font-size:10px">文中部分资料参考<a href="http://baike.baidu.com/link?url=A_XDsGJ5Jv8wp5yd4M1M-qyII9Qo-MsZqH1tMdU4b9IUfN7efszUdsuGsjLXe8A6zpcXZ91Mvifp7F7C0hlNua">百度百科</a>及腾讯ISUX( <a href="http://isux.tencent.com/responsive-web-design.html">http://isux.tencent.com/responsive-web-design.html</a>)</p>