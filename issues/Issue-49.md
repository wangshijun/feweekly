## 前端周刊第49期：React 和 Vue.js SSR 框架 + 微信小程序 + Grid 布局

> 本周收录的内容包含主流前端框架 React、Vue.js、Angular 的版本更新和周边扩展；CSS 方面，Grid 布局是值得关注的；开发效率方面：有 2 篇关于 Git、Webpack 的技巧。内容如下，请享用。

### 技术动态

#### [Angular 4.0.0 正式版发布](http://angularjs.blogspot.hk/2017/03/angular-400-now-available.html?utm_source=javascriptweekly&utm_medium=email)

Angular 近期发布了 4.0 正式版，笔者只能感叹前端社区的版本号真是越来越逆天了，4.0 版本与 2.x 版本几乎是完全兼容的，内含的改进包括：更小的文件体积、视图引擎的大幅度改进，能节省模板编译产生的代码 60% 左右，此外还提供了支持服务端渲染的项目参考、最新版本的 TypeScript 支持等。看起来 Google 在 Angular 上投入了很大的精力，你跟么？

#### [微信小程序 6 大新能力全面解读](https://mp.weixin.qq.com/s?__biz=MzI4ODUxNTczMA==&mid=2247484533&idx=1&sn=c128948bffaf65893e9d4c93289ab35e&chksm=ec3c7788db4bfe9e5a1d39ad9b4cf12a79d3c3a7d66ce2d2b3d871ac2d5b73e6db381a6e94ac&scene=21#wechat_redirect)

微信小程序在 3 月 27 日晚 10 点突然爆出大新闻。微信为小程序开放了 6 大新能力，在知晓程序的这篇文章中，你将看到小程序 6 大新能力的最靠谱解读。

#### [轻松一刻：left-pad 事件周年纪](https://twitter.com/i/moments/847043675364507648?utm_source=nodeweekly&utm_medium=email)

去年这个时候，JS 社区发生了让很多开源包和开发者奔溃的 "left pad" 事件，随后就有人唱衰 JS 社区，但是整个社区又做了很多事情来避免类似问题，这里是一些比较有趣的推特内容，无聊的时候可以看看。

### 文章教程

#### [通过实例搞懂 Grid 和 Flexbox 两种布局方式](http://tutorialzine.com/2017/03/css-grid-vs-flexbox/)

做前端的同学不光要着眼于 JS 的变化，CSS 领域也在不断演化，从早期的 table 布局，到后来的 div + css 布局，再到 flexbox 布局，现在出现了更好用的 grid 布局，对于新出的这两种，flexbox 和 grid 有何异同？对比起来可能学习更快。

#### [透视 webpack 构建，把 CommonsChunkPlugin 用到极致](https://medium.com/webpack/webpack-bits-getting-the-most-out-of-the-commonschunkplugin-ab389e5f318)

webpack 官方开发组在 twitter 上发起了一个活动，让大家使用 webpack-bundle-analyzer 把打包后的 webpack 依赖可视化截图发出来，然后给诊断 webpack 配置不合理的地方，这篇文章把大家典型的错误姿势做了纠正，你需要自己研究下，很大概率，你用的姿势也不对。

#### [声明 Vue.js 组件模板的 7 种姿势](http://vuejsdevelopers.com/2017/03/24/vue-js-component-templates/)

这篇文章梳理了声明 Vue.js 组件模板的 7 种方式，并举了比较具体的例子来说明，当然这其中方式在代码可读性、可维护性、模块化等方面都有不小的差别，你所要做的就是涨点只是，选取自己最舒适的。

### 开发工具

#### [最常用的 Git 奇技淫巧](https://github.com/git-tips/tips)

这里列出了超过 50 个 Git 相关的技巧，给出了每个技巧需要的命令和能解决的问题，想真正掌握 Git 操作？除了看 Git 内核之外，还需要对常用的命令勤加练习，这里就是练习秘籍。

#### [手把手教你配置 Webpack + Vue + TypeScript 开发环境](https://medium.com/@hayavuk/setting-vue-up-for-typescript-goodness-a6ddc4072f4f)

这篇文章先是花了不少篇幅跟你解释为什么要选择 .vue 文件的方式来做 Vue.js 开发，接下来是为什么选择 TypeScript，然后手把手教你如何配置他们的开发环境，如果你做类似事情的时候遇到问题，这会是不错的参考。

### 代码框架

#### [Vue Typeahead：输入框自动完成组件](https://github.com/pespantelis/vue-typeahead?utm_campaign=Revue%20newsletter&utm_medium=Newsletter&utm_source=revue)

Typeahead 这种交互方式已经很常见了，鼻祖就是 Google 的搜索建议，这是 1 个为 Vue.js 开发的输入框自动完成组件，做用户界面和管理后台的都应该能用得上。官网的 Demo 使用了 Twitter 的 API，使用可能不那么流畅，即使翻墙了也是如此。

#### [React 前后端同构应用框架 Next.js 发布 2.0 版本](https://zeit.co/blog/next2)

Next.js 在前端周刊第XXX期中已经收录，其出现的主要动机是提供一个前后端同构应用的脚手架，Github star 数量超过 1W，近期正式发布了 2.0 版本，其主作者在 React Conf 2017 上也 Next.js 做了演讲和布道，想在 React 前后端同构应用上少走弯路？强烈建议试试这个。

#### [Vue.js 前后端同构应用框架 Nuxt.js](https://github.com/nuxt/nuxt.js)

该项目受 React 领域中的 Next.js 启发而产生，主要目的是便利大家开发 Vue.js 服务端渲染的应用，诞生的还比较晚，目前还没有发布 1.0 正式版，保守的同学可以再等等。侧面反映了 Vue.js 在开发者群体中受欢迎的程度。

#### [Choices：轻量级的输入框、选择列表扩展插件](https://joshuajohnson.co.uk/Choices/)

Choices.js 提供了类似于 Select2 和 Selectize 的输入框和选择列表扩展功能，但是不依赖 jQuery，源代码很小，支持多种自定义配置，首页有常见业务场景中需要的标签输入框、多选列表、单选列表、级联选择的 Demo。

### 精彩问答

#### [为什么优秀的程序员喜欢命令行？](https://mp.weixin.qq.com/s?__biz=MzAxODI5ODMwOA==&mid=2666540615&idx=1&sn=43a27036709a4d65a086c6efd8ac5e95&chksm=80dceaecb7ab63fa14724d8ed890fd69001854a0088cd0c3055da7a66786d605aa811d335adc&mpshare=1&scene=24&srcid=0330HEHMv2zBX5bU89LMEntG&key=87f047796d9)

要给优秀的程序员下一个明确的定义无疑是一件非常困难的事情。擅长抽象思维、动手能力强、追求效率、喜欢自动化、愿意持续学习、对代码质量有很高的追求等等，这些维度都有其合理性，不过又都略显抽象和主观。这篇文章的作者有他独到的观点，我也非常赞同，文中列出了工程师可以通过命令行完成的很多事情。

#### [ES6 中的 const 到底意味着什么？](https://medium.com/the-node-js-collection/what-does-const-stand-for-in-es6-f7ab3d9e06fc)

const 是 ES6 中变量声明的新方式，表面意思是声明的变量不可被改变，从底层来看，到底是什么不可被改变？从其他语言转 JS 的同学可能会有些疑惑。用 const 声明的数组或者对象，或者类型实例能否被改变？能被怎样改变？你都清楚么？

#### [使用淘宝镜像加速 Electron、Node-Sass 的安装速度](http://zqlu.github.io/2016/05/10/taobao-nodejs-mirror/)

可以说淘宝的镜像给国内的开发者节省了很多时间，大到操作系统，小到各种工具。这篇短小的文章介绍了如何在项目中使用淘宝镜像为 Electron 和 Node-Sass 的安装加速，希望能缩短你的搭环境时间。

### One More Thing

如果对文中的内容有任何疑问，欢迎留言讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/p/25644447)。
