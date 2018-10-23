# Mpvue-Study-Note
mpvue学习笔记

 - Author: G-Dragon
 - Time:   2018-10-23


## 前 言

创建这个仓库的目的是将使用 `mpvue` 过程中的一些总结、思考、遇到的问题记录下来，一方面是对过程的记录，另一方面，书写可以让我更善于思考。最后，也希望我的日志对各位看官有用。

好了，下面用自己的话概括下 `mpvue` 是什么？优点有哪些？

**是什么？**
 - `mpvue` 是一款使用 `Vue.js` 开发微信小程序的前端框架。`mpvue` 是基于 `vue` 源码二次开发而来，使的它支持小程序平台, 即mpvue其实就可以看做是小程序版的 `vue`。但是，它的本质还是 小程序社区在探究小程序开发过程中提出的一一种技术方案。

**优点：**
 - 使用此框架，开发者将得到完整的 `Vue.js` 开发体验;
 - 为H5和小程序提供了代码复用的能力 (如果想将 H5 项目改造为小程序，或开发小程序后希望将其转换为H5，mpvue将是十分契合的一种解决方案。);



### 开始前几个问题

#### 为什么选择 `mpvue` 开发小程序

`mpvue` 是小程序开发中技术方案中的一个。`mpvue` 是基于 `vue` 源码进行的二次开发， 新增加了小程序平台的支持 —— 也就是小程序版 `vue`;

下面，正式回答标题问题：
 - `mpvue` 让 `Vue.js` 的开发者以低成本接入小程序开发;
 - 另外，做到代码的低成本迁移和复用;
 - 其次，提供了一些原生小程序不具备的特性；



## 开始

### 小程序版本的 Vue.js

正如标题 **“小程序版本的vue.js”**, 这句话来自官网文档，官方介绍是下面这样的：

> mpvue （github 地址请参见）是一个使用 Vue.js 开发小程序的前端框架。框架基于 Vue.js 核心，mpvue 修改了 Vue.js 的 runtime 和 compiler 实现，使其可以运行在小程序环境中，从而为小程序开发引入了整套 Vue.js 开发体验。



##　性能优化



## 学习资料

### 文档
 - [mpvue官网文档](http://mpvue.com/)

### 一些使用mpvue开发的项目
 1. ezchinese-用mpvue写得打卡小程序： 
 2. [嘎嘎记单词]( https://github.com/gagaprince/BrainStormWxApp)
 3. [MpUI 是一套基于 weui-wxss 开发的 mpvue 组件库，增加了一些新的特性、样式和组件](https://gon.gyeq.in/mpui/#/)
 4. [个人博客小程序版](https://github.com/overxue/mpblog)
 5. [豆瓣电影](https://github.com/mini-mpvue/mpvue-douban)
 6. [用mpvue写的小程序版的cnode社区](https://github.com/jaxQin/mpvue-cnode)
 7. [一个基于mpvue的弹窗组件](https://github.com/noahlam/mpvue-toast)
 8. [美食搜索 小程序](https://github.com/xiaoshengkai/mpvue-FG)
 9. [使用mpvue实现的github小程序端](https://github.com/cheesekun/wx-github)
 10. [极客教程 微信小程序版](https://github.com/cllgeek/geekjc-weixin)
 11. 仿追书神器的小说阅读器小程序 https://github.com/zprial/wx-book


最后，如果你有什么mpvue作品，请和大家分享：https://github.com/Meituan-Dianping/mpvue/issues/21
