## 前端周刊第50期：React 状态管理 + Vue.js 作弊条 + 命令行技巧

> 因为休假今晨返京，所以本期内容发周日晚才发出来。本期在 IDE、命令行、React、Vue 等方面都有涉及，还收录了 csswizardry 博主的开发环境和装备。以下是精选内容，请享用。

### 技术动态

#### [React v15.5.0 正式版发布](https://github.com/facebook/react/releases)

Facebook 近期发布了 React v15.5.0 小版本，该版本的变化主要包括增加 CreateClass 和 PropTypes 的弃用警告和部分 Bugfix，具体可以参照原文，需翻墙。

#### [Dropbox：Brotli 静态资源压缩算法实战](https://blogs.dropbox.com/tech/2017/04/deploying-brotli-for-static-content/)

这篇文章来自 Dropbox 工程团队，他们在自己的服务中部署了 Brotli：比 gzip 压缩还要小 20% 的压缩算法，用于提供静态资源，文中有详细的数据、实现方案、以及部署之后发现的问题。

### 文章教程

#### [async/await 甩 Promise 几条街的 6 大理由](https://hackernoon.com/6-reasons-why-javascripts-async-await-blows-promises-away-tutorial-c7ec10518dd9)

Node.js v7.6.0 中已经天然开启了 async/await 特性的支持，如果你还不知道他们是啥，放下手头的事情研究下先。async/await 可以说是更加优雅的 JS 异步处理方式，写出来的代码比 Promise 更加简洁，这里列出了 6 大理由，哈哈~

#### [Grid Garden：交互式的 Grid 布局学习园地](http://cssgridgarden.com/)

Grid Garden 是一个交互式的 Grid 布局学习园地，代码和演示并排展示，一步步教你学会 Grid 布局的各种属性。

#### [如何处理 Node.js 中的 Unhandled Promise Rejection](http://thecodebarbarian.com/unhandled-promise-rejections-in-node.js.html?utm_source=javascriptweekly&utm_medium=email)

Node.js 从 V6.6.0 开始，会在命令行中把未处理的 Promise Rejection 打印成 Warning，而 Promise Rejection 通常意味着我们的应用抛出了错误，未来的 Node.js 版本遇到 Promise Rejection 会直接抛错而不是简单的警告，我们在现在的代码中该如何处理这种问题？有什么坑？都在这篇文章里啦。

#### [MobX vs Redux: Comparing the Opposing Paradigms](https://mp.weixin.qq.com/s?__biz=MjM5MTA1MjAxMQ%3D%3D&amp;mid=2651226268&amp;idx=1&amp;sn=3eb78e7933ba951d1b8d6b9d69a240be&amp;chksm=bd4959188a3ed00e1c941d8893fd2b496ed0afd648b8b1a8b7c301178ba0e5fd52f681ade723&amp;scene=0&amp;key=87f047796d968ecc232ede698)

Redux 与 MobX 是 React 生态中最火热的状态管理工具，社区也一直没有停止对上述两者的讨论。在不久前结束的 React Conf 2017 中，Preethi Kasireddy 也做了相关分享，MobX vs Redux: Comparing the Opposing Paradigms，让我们来看看她的观点是怎样的。英文好的同学可以去 Youtube 上看视频。

#### [你看不到的 CSS 属性](https://madebymike.com.au/writing/the-invisible-parts-of-CSS/)

前端日常工作中，你的首要目标可能就是让页面元素看起来跟设计图完全相同，实现目标的过程跟结果相比起来可能并不是那么重要，这也意味着，使用 CSS 的时候，我们会更关心视觉效果而不是 CSS 究竟是如何工作的，有过部分工作经验的同学可能已经意识到，CSS 代码的视觉效果会受到部分不可见属性的影响，比如 display 属性，怎样才算是真的掌握了 CSS ？通过这篇文章认真学习不可见属性。

### 开发工具

#### [Reactide：专门为 React 定制的 IDE](https://github.com/reactide/reactide)

Reactide 是收款专门为 React 定制的集成开发环境，支持 Windows、Mac，目测也是使用类似于阿童木的技术编写的，使用 Reactide 开发 React 应用不需要任何配置，你只需要打开文件、编辑、保存，就能预览效果。还在早期开发阶段，有兴趣的同学可以试试。

#### [bash 入门学习指南](https://github.com/Idnan/bash-guide)

第 49 期周刊中有篇题为《优秀的程序员都喜欢命令行》的文章，而 bash 是众多命令行环境中的经典，这篇文章列出了能够在 bash 中完成的各种操作，比如文件、目录、文本、网络等，没有非常复杂的参数讲解，非常适合入门。

#### [通过 .npmrc 打磨你的 Node.js 开发环境](https://nodesource.com/blog/configuring-your-npmrc-for-an-optimal-node-js-environment)

对于 Node.js 开发者来说，每天使用 npm 命令行的次数恐怕是仅次于编辑器的，Node.js 生态的蓬勃发展离不开 npm，npm 命令行工具是高度可配置和自定义的，这篇文章列出了可以通过 .npmrc 来完成的优化你开发环境的全局配置。

#### [Harry Roberts 的开发环境和装备](https://csswizardry.com/uses/)

不知道 Harry Roberts 的同学总该知道 csswizardry.com 这个网站吧，他就是这个网站的博主，他在这篇文章中贴出了自己的开发环境和装备，工欲善其事必先利其器，如果你想效率非常，对开发环境的调校和练习是必不可少的。

### 找找灵感

#### [Vue.js 2.2 API 作弊条](https://vuejs-tips.github.io/cheatsheet/)

这个作弊条完整列出了 Vue.js 2.2 版本的全部 API，并且附上了到官方文档的链接，排版也一目了然，喜欢使用作弊条的同学可以打印出来了。

#### [调用 JS 函数的 11 种姿势](https://gist.github.com/myshov/05800f083a0afce56e0f782314a103eb?utm_source=javascriptweekly&utm_medium=email)

这个 gist 列出了调用 JS 函数的 11 种姿势，然后给大家挖了一个大坑，后面的评论区还有不少补充，估计大多数同学只用过其中的几种，站在个人角度，冷门的方式不建议用，但是站到你面前，你要能认出来。

### 精彩问答

#### [如何通过 HTTP Header 让你的应用更安全？](https://www.smashingmagazine.com/2017/04/secure-web-app-http-headers/)

这篇发表在 smashingmagazine 的文章介绍了如何通过设置恰当的 HTTP Header，让你的应用更安全，具体来说就是如何避免被人内嵌、如何避免 XSS、如何避免被缓存、如何避免点击劫持、如何避免嗅探。严肃的工程师都应该把这些安全措施用到实际项目中。

#### [工程师面试为什么要考算法和写代码？](https://mp.weixin.qq.com/s?__biz=MjM5ODIzNDQ3Mw%3D%3D&amp;mid=2649966803&amp;idx=1&amp;sn=6485fd28c30d5b7c711d00a89f2e82cc&amp;chksm=beca38d589bdb1c313cf18d229603dbbb575938e467ce1b6eb233c2c118f14c9df3f47bf6a53&amp;mpshare=1&amp;scene=24&amp;srcid=0331wM4Q)

很多面试工程师职位的抱怨，为什么面试的时候老是要考什么算法呀，还要现场写代码？弄得大家天天去刷面试题，这些有什么用？这篇文章聊了这么做的原委，笔者非常赞同。不是为了考算法而考算法，面试官需要在短暂的面试时间内确定候选人是否够聪明、是否能出活。

### One More Thing

如果对文中的内容有任何疑问，欢迎留言讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

