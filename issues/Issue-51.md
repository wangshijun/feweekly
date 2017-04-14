## 前端周刊第51期

> Node.js 社区最高产的工程师 <a href="https://twitter.com/sindresorhus/status/851843817888137217">Sindre Sorhus</a> 本周发布了他的第 1000 个 npm 包，<a href="https://github.com/sindresorhus/conduct">详见这里</a>，据 npm 官方统计，全网的 npm 包下载量中有 12% 都跟 Sindre Sorhus 有关。看到这个，你作何感想？

另外，部分精彩的文章我已经翻译成中文发到<a href="https://zhuanlan.zhihu.com/feweekly">知乎专栏</a>上，就没有收录到前端周刊。下面是本周的精选内容，请享用！

### 技术动态

#### [谷歌推人工智能绘图工具 AutoDraw](https://www.autodraw.com/)

AutoDraw 是谷歌推出的人工智能绘图工具，能根据你的手稿作为启发式信息，然后列出你可能想画的内容，对于画画不好的同学可能会很有帮助，不画画没关系，当个玩具也可以。为什么发在前端周刊？你对它的前端是怎么做不感兴趣么？

#### [Vue Conf 2017 报名入口](https://vue.w3ctech.com/)

全球首届 Vue.js 开发者大会将于 2017 年 5 月 20 日在北京航空航天大学新主楼会议中心举办。Vue.js 作者将出席本次大会，并发表主题演讲。这里是报名入口，早鸟票当天就被抢光了，你如果有女朋友，可以带过去，哈哈！

#### [微信公众号可以注销了](https://mp.weixin.qq.com/s?__biz=MjM5NjM4MDAxMg==&mid=2655074573&idx=1&sn=cb31b7bc6332f2cd302a9dd6dcf96bd7&chksm=bd5fb50e8a283c18a19d1949b862906fce8ffeb1f139331e553014bdd94a32e8a1193e18de32&mpshare=1&scene=2&srcid=0412UHDOcVqMiWEHsI7702ck&key=92f5eb06f6e0)

微信公众号近期宣布支持自主注销，用户在核实身份信息或者验证帐号主体后，可以在公众号后台发起注销流程。帐号完成注销后，主体注册次数、运营者身份证信息、手机号码、帐号昵称、管理员微信号、注册邮箱等，均可释放。

#### [如何评价微软开源的 ReactXP ？](https://www.zhihu.com/question/58247259)

微软在开源领域动作越来越多，上周开源了 ReactXP，生成能开发跨平台的 React 应用，怎么客观的评价这个动作呢？看看知乎上大家的讨论。

### 文章教程

#### [图解 Chrome 中的滚动锚定机制](https://blog.google/products/chrome/taking-aim-annoying-page-jumps-chrome/)

看到这个的时候，再次感慨 Google 做产品就是在做用户体验，不知道你没有遇到过，打开了一个长页面，已经开始阅读，突然页面跳了一下，丢失了你的浏览进度，这通常是因为你看的内容上面还有未加载完成的内容，它加载完就把下面的内容挤下去，产生页面跳跃的感知。Chrome 浏览器已经对这种体验问题做了优化，用了叫做 Scroll-Anchroing 的技术，技术方案细节在本文内的某个链接上。

#### [集成 Nuxt.js 到现有的 Node.js 项目](https://blog.feathersjs.com/ssr-vuejs-app-with-feathers-and-nuxt-bb7dfd3e6397)

Nuxt.js 是基于 Vue.js 的前后端同构应用脚手架，Feathers 是 Node.js 的 MVC 框架，当然绝大多数同学在公司不会是从头开始一个新的项目，这篇文章讲了如何把 Nuxt.js 集成到现有的 Feathers 应用中去，对其他的 MVC 框架也有参考价值。

#### [酷壳：如何重构“箭头型”代码？](http://coolshell.cn/articles/17757.html)

“箭头型代码”如果嵌套太多，可能看起来很美，因为对称，但是读起来想吐血，因为太长，会相当容易让维护代码的人（包括自己）迷失在代码中，因为看到最内层的代码时，你已经不知道前面的那一层一层的条件判断是什么样的，代码是怎么运行到这里的，所以，那怎么能不写出这种代码呢？这篇文章提供了思路。

#### [Chrome 里面的 Coverage 功能到底是如何工作的？](http://www.mattzeunert.com/2017/03/29/how-does-chrome-code-coverage-work.html)

我本周发了篇文章介绍 Chrome Canary 里面的运行时代码覆盖率功能，这篇文章从源代码的层面研究了这个代码覆盖率功能到底是怎么实现的，文中有彩蛋，看到你就会自己开发 Dev Tools 啦。

### 开发工具

#### [GitHub：开源项目运维自动化工具箱](https://github.com/showcases/tools-for-open-source)

GitHub 官方整理的能帮助你运维开源项目的工具列表，能把日常的大部分运营工作自动化，比如代码风格检查、持续集成、包管理、变更日志生成、自动找 Reviewer、依赖包过期提醒。说实话，大部分工具其实可以用到公司内部的工程化实践中，前提是你愿意花时间去学习折腾。

#### [alinode：基于 Node.js 运行时的应用性能管理解决方案](https://alinode.aliyun.com/)

官方说法：alinode 是阿里云出品的 Node.js 应用服务解决方案，帮助开发者迅速洞见性能细节，快速定位疑难杂症，直探问题根源。我的说法：没有调查就没有发言权，准备近期使用，之后总结心得出来。

### 代码框架

#### [React Native 微信功能集成实例](https://github.com/weflex/react-native-wechat?utm_campaign=explore-email&utm_medium=email&utm_source=newsletter&utm_term=weekly)

该仓库在 React Native 中集成了微信登录、收藏、分享、付款功能，支持 Android 和 iOS 版本，如果你最近在研究 React Native，接下来你很可能会有类似的需求。

#### [VMS：基于 Vue.js 2.0 的 CMS 系统](https://github.com/ericjjj/vms)

类似项目收录过两个，前端类似 vue-admin，但是包含了完整的 Node.js 后端，有比较简单的权限控制（对于复杂的应用略显简陋），集成了常见的后台管理所需的组件：如 WangEditor 富文本编辑器、轻量级 Markdown 编辑器、七牛云图片上传、极光推送等。


### 视频教程

#### [使用 Nuxt.js 和 Vuex 构建 Vue.js 服务端渲染应用](https://egghead.io/courses/build-a-server-rendered-vue-js-app-with-nuxt-and-vuex?utm_content=bufferb6553&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

Nuxt.js 和 Vuex 是啥这里就不废话了，来自 egghead.io 的课程，从 0  开始，教你如何如何使用 Next.js 来组织应用代码，Vuex 管理状态。

### 精彩问答

#### [toolingtips：如何在 git grep 的时候默认显示行号？](http://stackoverflow.com/questions/11107059/how-to-show-line-numbers-by-default-with-git-grep-command)

Git 相信很多人都熟悉，grep 自命令可用来快速查找，但是默认的查找结果不显示匹配的代码在哪一行，这其实不利于效率的提升，因为大概率你定位到文件之后还要去文件里再搜一遍才能定位到行，为什么不一步搞定呢？看看这里的第 2 个答案，修改的文件时 ~/.gitconfig。

#### [toolingtips：如何高效的操作 Mac 中的 Finder 和截图](http://apple.stackexchange.com/questions/400/please-share-your-hidden-macos-features-or-tips-and-tricks?answertab=votes#tab-top)

Mac 中的文件系统管理器 Finder 和截图相信是很多人常用的，这个帖子里面有些小技巧能让你事半功倍，至少不依赖第三方软件，你确定不去看看？注意是第 1 和第 3 个答案。

#### [toolingtips：如何让 mongoose 填充嵌套的关联字段](http://stackoverflow.com/questions/19222520/populate-nested-array-in-mongoose)

超过 3 个表的关联在复杂的业务中非常常见，mongoose 中有个 populate 查询语法，可以按字段填充关联表里面的数据，那怎么填充嵌套的关联表数据呢？看这里的第2 个答案。顺道吐槽下 mongoose 的文档，谁看谁恶心。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking
