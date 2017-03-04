## 前端周刊第45期

> 这周发生了很多大事，百度挂完亚马逊挂，斯坦福还准备开 JS 课程，看来订阅这份周刊的同学都没入错行。先纠正我之前的一个错误，就是对于 Node.js 的叫法，有写过 NodeJS 的，也有写过 Node 的，但是官方的叫法是 Node.js。下面是本周的精彩内容，请享用！

### 文章教程

#### [编写 Node.js Rest API 的 10 个最佳实践](https://zhuanlan.zhihu.com/p/25506654)

Node.js 除了用来编写 WEB 应用之外，还可以用来编写 API 服务，本文会介绍编写 Node.js Rest API 的最佳实践，包括如何命名路由、如何选择框架、如何进行认证和测试、如何发送元数据等话题。翻译自 RingStack。

#### [Node.js 最新 WEB 技术栈](https://cnodejs.org/topic/56fdf66ec5f5b4a959e91771)

由 Node.js 领域的狼叔整理，里面涵盖了使用 Node.js 开发 WEB 应用的方方面面，按照他的路线图，要不了多久，你也能成为 JS 全栈工程师。

### 开发工具

#### [Lerna：帮你管理包含多个 package 的 JS 项目的工具](https://lernajs.io/?utm_source=nodeweekly&utm_medium=email)

Lerna 是一款能够帮你管理包含多个 package 的 JS 项目的工具，能够带来的便利是主 package、子 package 发版的管理，可能部分同学没有这种痛点，但是如果你留心过大型的开源项目比如 webpack、babel 等的源代码就会发现，这些项目都包含很多个 package，他们都用了 Lerna。

### 代码框架

#### [Store.js：跨浏览器的通用浏览器端存储方案](https://github.com/marcuswestin/store.js)

Store.js 是跨浏览器的浏览器端通用存储解决方案，会根据浏览器的支持情况智能选取最合适的存储介质，目前发布了 2.0 版本，对于开发单页应用的同学来说，是非常值得看看的。

#### [CSSIcon：使用纯 CSS 实现的图标库](https://github.com/wentin/cssicon)

这是使用纯 CSS 实现的图标库，没有任何依赖，你可以直接把 CSS 复制粘贴了拿去用，里面包含了不少常用的其他图标库需要依赖字体或者图片才能实现的图标，对动画的支持当然不在话下。

#### [HyperApp：小巧的、类 Elm 架构的 WEB 应用构建框架](https://github.com/hyperapp/hyperapp)

HyperApp 是小巧的、类 Elm 架构的 WEB 应用构建框架，主要特性为声明式、无状态、内置 JSX 支持。小巧到什么程度呢？无任何依赖，只有 1KB 大小。喜欢折腾的同学可以看看。

#### [Node.js 中角色和权限功能相关的库](https://gist.github.com/facultymatt/6370903)

现代软件系统不管是面向用户的还是企业内部的，权限控制都会是不可或缺的一部分，这篇 gitst 收录了 Node.js 中跟角色权限相关的各种库，包含了多种实现的模型。

### 找找灵感

#### [Vue.js NewsLetter](https://www.getrevue.co/profile/vuenewsletter)

类似于前端周刊的，但是主题聚焦在 Vue.js 方面，Vue.js 这款国产框架最近1年被采用的势头非常的迅猛，如果你正在学习，这个不容错过！里面也是收录了大量的内容，不过是英文的。

### 视频演讲

#### [QQ 会员活动运营平台架构设计实践](http://hansionxu.blog.163.com/blog/static/2416981092016295202426/)

腾讯技术大牛在 SDCC 上所做的分享，详细展示了 QQ 会员活动运营平台架构设计实践，面临的挑战、解决方案，容量、安全、效率等方面的考量。如果想成为前端架构师，这种学习不可少！

### 精彩问答

#### [图片的 display 设置为 none 到底会不会下载？](https://stackoverflow.com/questions/12158540/does-displaynone-prevent-an-image-from-loading)

很多同学可能会认为，把图片的样式属性 display 设置为 none 浏览器就不会下载他了，我最近发现业务上有个加载慢的页面就是因为这种认识导致的，实际上结果不是二分的，而是随着浏览器的进化答案不同。

#### [如何优化 CPU 密集型的 Node.js 应用？](https://medium.com/@graeme_boy/how-to-optimize-cpu-intensive-work-in-node-js-cdc09099ed41#.efm219a5y)

通常来说 Node.js 只适合于开发 IO 密集型的应用，但是有时候你可能也会拿他来开发 CPU 密集型的任务，这种情况下也是有办法来进行一些优化，来实现更高的性能的，这篇文章帮你解惑。

#### [JS 中的 void 到底有啥用？](http://cmichel.io/javascript-void-keyword/)

JS 中的 void 到底有啥用？没见过？这次算是开眼，见过？那你知道他是用来干嘛的么？这篇文章都给你解释清楚了。

### 技术动态

#### [斯坦福大学准备使用 JS 来做计算机入门课程](http://www.stanforddaily.com/2017/02/28/cs-department-updates-introductory-courses/)

有人预言说，能用 JS 写的，最终都会用 JS 写，我印象中国内外没有一家学校开设了 JS 或者前端课程，但是斯坦福大学走在了前面，准备采用 JS 作为计算机科学导论的编程语言，并为此做好了充分准备。

#### [AWS 的 S3 故障回顾和思考](http://coolshell.cn/articles/17737.html?from=timeline&isappinstalled=0)

继 GitLab 的误删除数据事件没几天，“不沉航母” AWS S3 几天前也“沉”了 4 个小时，墙外的半个互联网也跟着挂了。按 AWS 惯例，AWS 今天给出了一个简单的故障报告，简单来说这个故障和 GitLab 一样，也是人员误操作，他们是什么态度？后续怎么解决、完善？相信很值得借鉴。

#### [Visual Studio Code V1.10 发布](https://code.visualstudio.com/updates/v1_10#_preview-minimap)

Visual Studio Code 可以说是微软发力之后的奋起直追，目前已经在前端开发者中占有了不小的时长份额，本次发版包含了大量改进，比如：Minimap 给你提供代码的鸟瞰图、编辑器内的文本拖拽支持、自动生成 JSDoc 等。

### One More Thing

想直接在微信中订阅前端周刊？扫下方二维码关注前端周刊订阅号。
![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)


想和我面对面交流？扫下方二维码添加我为好友。

![wangshijun](http://www.feweekly.com/img/src/weekly/feweekly/wangshijun.jpg)

Happy Hacking

