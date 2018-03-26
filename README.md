项目名：微信小程序资料收集，Git 仓库地址：https://github.com/zhaotoday/mini-program 。

## 1. 介绍

### 1.1. 小程序是什么

- 定义：小程序是一种全新的连接用户与服务的方式，它可以在微信内被便捷地获取和传播，同时具有出色的使用体验；
- 特点：无需安装、触手可及、用完即走、无需卸载；
- 英文：mini program。（注：应用、App 之类的词被苹果公司和谐）

### 1.2. 有趣的比喻

- App 就像原配，一年用不了几次；
- 服务号就像小三，每个月固定用几次；
- 小程序就像炮友，用完即走。

### 1.3. 运行环境

| 运行环境	      | 逻辑层	       | 渲染层         |
| --- | --- | --- |
| iOS	          | JavaScriptCore | WKWebView      |
| 安卓	          | X5 JSCore	   | X5浏览器       |
| 小程序开发者工具 | NWJS	       | Chrome WebView |

## 2. 网址

### 2.1. 官网入口

- [微信公众平台](https://mp.weixin.qq.com/)  
- [微信小程序简易教程](https://mp.weixin.qq.com/debug/wxadoc/dev/index.html)  
- [微信小程序开发者社区](https://developers.weixin.qq.com/)
- [微信小程序开发者工具](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/devtools.html?t=20161122)   

### 2.2 推荐网站
- [第九程序](http://9.cn)
- [微信小程序联盟](http://www.wxapp-union.com/)
- [微信小程序开发资源精选网址导航](http://www.yimijili.com/xcxwzdh.html)

### 2.3 小程序导航网站
- [小程序商店](http://xcx.9.cn)
- [小程序商店](http://www.91ud.com/)
- [小程序窝](http://www.xcxwo.com/)
- [微信小程序导航](http://www.w3cschool.cn/miniapp)
- [小程序应用商店](http://www.51westore.com/)
- [知晓程序](https://minapp.com/miniapp/)
- [微信小程序大全](http://www.duba.com/wxapp/)
- [小程序商店](http://www.xcx.la/)
- [小程序商店](http://www.xcxsdw.com/)

## 一些限制
这些限制导致现在的小程序功能不全、体验不佳、没有维护运营。 [链接](http://9.cn/news/501)
- 不开放线上流量，导致很多开发者撤出
- 体积受限1M以内，很多App只能做裁剪版
- 开放的API太少，很多原生功能无法实现
- 界面UI被框死，无法与原生一致
- 不能方便安装到手机桌面
- 开发和运维工作只能单独一条线为微信服务，投资大回报不佳

## 如何打开小程序
- 微信小程序无法分享到朋友圈，甚至无法通过长按二维码进入，也就是说，即使你在一个网页或一篇订阅号的文章里放上小程序的二维码，用户还是无法长按打开小程序。  
- 用户只能通过：线下扫码、搜索、朋友分享来打开小程序。  
- 微信人为地限制了小程序的线上导流，通过主动搜索进入，量显然不会特别大，朋友之间的分享，扩散的速度也有限，可以说，微信在逼迫开发者尝试线下的导流渠道。

## 最新消息
- [2016-12-29 更新] 微信小程序将于 2017-1-9 正式上线 [链接](https://mp.weixin.qq.com/s?__biz=MjM5NTE4Njc4NQ==&mid=2657611912&idx=1&sn=f91c228764f9a3b4ed696276fae1ee1b&chksm=bd6f01868a188890c72c32e3082f2bc36d7f79efab345a9a58595a4a19c9fa39f522e9981b2d&mpshare=1&scene=1&srcid=1228p6Hph7jd2lUOkbCGL7x6&key=564c3e9811aee0ab29c2072d6a92477a8d62ef0e5fe510df5d0ad41c92368cae49761c048dff4fe55f719d3c57afc1710797e0a290516f8f860e49c4ee3a25d3300f54e11fb682ebd3fa99faaedbc661&ascene=0&uin=MTk0MTE1NDU%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.12.2+build(16C67)&version=12010210&nettype=WIFI&fontScale=100&pass_ticket=%2F7fUB762zG7R6Di%2FQtIMesFlLkcdP9nx1gv2wrmlrq0%3D)

## 实际例子
- 实体店购物：我们在线上购物的时候，不仅关注价格，也关注产品的评价，作为购买的依据。而传统的线下商品是看不到评价的和无法互动的，但是有了小程序二维码，可以扫码打开小程序，看到购买过该商品的人的评价、衣服珠宝类穿在身上的照片，有利于线下销售。另外也可以引导到店客户，结合线上做活动，为商品做促销传播，比如拼团等。
- 代驾：与朋友喝酒了，直接在餐桌上扫码，打开代驾小程序快速方便找代驾。
- 医院排队：生病去医院，挂号、拿药、交钱，提高效率。
- 饭店：排队等位、餐位预订、多人同时点菜、移动支付。
- 车站：无须排队，自助购票。
- 上门维修：维修师傅制服上一个二维码，顾客直接扫二维码对该师傅进行评价和支付。
- 停车收费：地下停车场无需设置人工收费处，扫码支付。
- 用户到达线下某个餐馆就餐时，不需要下载这个餐馆的 APP，只需要在餐馆扫一下它的二维码，然后就可以在这个餐馆的小程序里排队或者点餐；
- 在公交车站，你扫一下公交站牌的二维码就可以了解下一辆公交车到站的时间；
- 在汽车站，扫一下汽车站的二维码就可以购买车票，而不需要排长队。
- 比如一家餐厅利用小程序制作一个菜单，用户抵达餐厅，扫一扫，点菜，付款完事，对于一家餐厅来说，在各种方面均可以降低成本提升效率，用户也获得了便利。[链接](http://www.woshipm.com/it/573821.html)
- 或者说我们到了一个商场逛一个品牌（或者是超市购物），衣服上再也不需要条码，取而代之的是二维码，我们在一家店内看中一件衣服，只需扫一扫衣服上的二维码便可以进入衣服的详情页（暂且忽略小程序的制作成本），不仅可以看到尺码信息，模特图，还可以看到用户评论，中意的话最后完成购买结算，整个流程貌似更加顺畅，同时解决了线下购物的一些痛点。[链接](http://www.woshipm.com/it/573821.html)
- 2017年1月1号的时候，去上海迪士尼玩了一圈，通过知乎网友的帮助，提前下了迪士尼的官方App，可以查看电子导览图，排队时间等，特别方便，貌似国内的其它游乐场没有提供这项便捷服务。但是一天游玩结束后就把App删了，看上去好浪费。如果全中国的旅游景点，或者游乐场所都开发类似的小程序？我觉得是可行的。毕竟是对用户来说是低频刚需，但是对园区来说，小程序成本更低，再加上用户方的低频需求乘以一个非常大的基数便会是一个非常可观的效应，或许再结合一下VR和AR技术，还可以有更多的可能性。

## 框架
- [weui-wxss - WeUI for 小程序](https://github.com/weui/weui-wxss)  
- [Labrador - 微信小程序模块化开发框架](https://github.com/maichong/labrador)  
- [wepy](https://github.com/wepyjs/wepy)  
- [Wafer - 企业级微信小程序全栈方案](https://github.com/tencentyun/wafer)  

## 工具
- [Egret Wing - 支持微信小程序实时预览的IDE](http://developer.egret.com/cn/github/egret-docs/Wing/update/update323/index.html)  
- [wept - 微信小程序 web 端实时运行工具](https://github.com/chemzqm/wept)  
- [微信小程序可视化设计工具](http://www.coolsite360.com/wxapp/)  
- [腾讯云 - 微信小程序解决方案](https://www.qcloud.com/solution/la.html)  
- [腾讯云 - 小程序配置指引、升级方案](https://github.com/tencentyun/weapp-doc)  

## 观点
- 小程序主推线下场景，除了带着腾讯「连接一切」的目的，其实也迎合了挖掘线下流量的趋势。[链接](https://kenengba.com/post/3538.html)
- 跟小程序比较般配的包括电商类、生活服务类、工具类、O2O、自媒体和企业级应用。[链接](http://www.cwechat.org/article-24-1.html)
- 整体看来，中小型企业、020服务类、线下门店、个人创业者等，均可背靠微信这颗大树在未来发家致富！[链接](http://www.wxapp-union.com/portal.php?mod=view&aid=659)
- 张小龙对小程序的定位明显是一个「工具型」的产品，如何建立最短路径然后帮助用户直达产品功能就是一个「好的工具」。从在这一点上来看，目前已经上架的「滴滴出行」小程序就是一个最好的范例，打开小程序就能直接获取用户当前位置作为起点，然后用户输入终点之后就能开始呼叫用车，一气呵成。 [链接](https://gold.xitu.io/post/5875df0561ff4b005c5c1db5?utm_source=gold_browser_extension)
- 从外部看到的信息来看，微信似乎更偏向于连接线下。[链接](https://kenengba.com/post/3538.html)

## 文章
- [提交小程序时需要注意什么？这三点你都必须知道](http://9.cn/news/290)
- [你好，我是小程序！官方公开课解说小程序开放](http://www.wxapp-union.com/article-1039-1.html)
- [2016微信数据报告发布](http://mp.weixin.qq.com/s/7FnrGvlN__iww57e91d0Ig)
- [微信小程序常见问题集合](http://www.wxapp-union.com/forum.php?mod=viewthread&tid=23)
- [野狗 SDK (微信小程序版) 正式发布](https://blog.wilddog.com/?p=1926)  
- [微信小程序：开发之前要知道的三件事](http://www.wxapp-union.com/portal.php?mod=view&aid=417)  
- [产品和运营自学小程序最好用的4个方法](http://www.wxapp-union.com/portal.php?mod=view&aid=414)  
- [微信小程序新手跳坑指南21条](http://www.wxapp-union.com/portal.php?mod=view&aid=663)  
- [微信小程序应用前景剖析](http://www.wxapp-union.com/portal.php?mod=view&aid=629)  
- [极欧杨勇：你的产品到底适不适合微信小程序？](http://www.wxapp-union.com/portal.php?mod=view&aid=609)  

## GitHub
- [微信小程序入坑指南](https://github.com/wxdev/app-guide)
- [微信小程序开发技巧](https://github.com/Romeo0906/WeChatAPP/blob/master/Something-that-wxadoc-don't-tell-you.md)
- [微信小程序开发资源汇总](https://github.com/justjavac/awesome-wechat-weapp)
- [微信小程序开源项目库汇总](https://github.com/opendigg/awesome-github-wechat-weapp)

## 视频教程
- [WXOPEN.Club 出品微信小程序开发视频教程（持续更新中...）](http://wxopen.club/topic/582d4999745f85100cd13a65)  
- [全网首个微信小程序开发视频教程](http://www.howzhi.com/course/15035/)  
- [微信小程序开发实战第一季(CSDN)](http://edu.csdn.net/course/detail/3011)  
- [微信小程序开发实战第二季(CSDN)](http://edu.csdn.net/course/detail/3045)  
- [极客学院微信小程序开发](http://www.jikexueyuan.com/zhiye/course/34.html?type=8&utm_source=jike&utm_medium=www_index_cf&utm_campaign=wechat_app&utm_content=0930)  
- [微信小程序新手入门(51CTO)](http://edu.51cto.com/course/course_id-7242.html)  
