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

### 2.1. 官网

- [微信公众平台](https://mp.weixin.qq.com/)  
- [微信小程序简易教程](https://mp.weixin.qq.com/debug/wxadoc/dev/index.html)  
- [微信小程序开发者社区](https://developers.weixin.qq.com/)
- [微信小程序开发者工具](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/devtools.html?t=20161122)   
- [微信小程序常见 Q&A 官方](https://developers.weixin.qq.com/blogdetail?action=get_post_info&lang=zh_CN&token=&docid=0008ec49d849681c05866d9a957008)

### 2.2. 推荐网站

- [第九程序](http://9.cn)
- [微信小程序联盟](http://www.wxapp-union.com/)
- [微信小程序开发资源精选网址导航](http://www.yimijili.com/xcxwzdh.html)

### 2.3. 小程序导航

- [小程序商店](http://xcx.9.cn)
- [小程序商店](http://www.91ud.com/)
- [小程序窝](http://www.xcxwo.com/)
- [微信小程序导航](http://www.w3cschool.cn/miniapp)
- [小程序应用商店](http://www.51westore.com/)
- [知晓程序](https://minapp.com/miniapp/)
- [微信小程序大全](http://www.duba.com/wxapp/)
- [小程序商店](http://www.xcx.la/)
- [小程序商店](http://www.xcxsdw.com/)

## 3. 开发资源

### 3.1. 框架

- [WePY](https://github.com/Tencent/wepy)
- [mpvue](https://github.com/Meituan-Dianping/mpvue)
- [weui-wxss - WeUI for 小程序](https://github.com/weui/weui-wxss)
- [Wafer - 企业级微信小程序全栈方案](https://github.com/tencentyun/wafer)  

### 3.2. 工具

- [wept - 微信小程序 web 端实时运行工具](https://github.com/chemzqm/wept)  
- [微信小程序可视化设计工具](http://www.coolsite360.com/wxapp/)  
- [腾讯云 - 微信小程序解决方案](https://www.qcloud.com/solution/la.html)  
- [腾讯云 - 小程序配置指引、升级方案](https://github.com/tencentyun/weapp-doc)  

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
