## 前端周刊第52期

> 哈哈，互联网圈本周的大事件是微信公众号关闭 iOS 平台打赏入口，讨论这件事情的文章很多，前端周刊就没有收录相关文章。回到技术本身，我读到 3 篇非常不错的如何写出更简洁代码的文章：<a href="http://jrsinclair.com/articles/2017/indentation-is-the-enemy-less-complex-javascript/">缩进就是复杂性</a>、<a href="http://jrsinclair.com/articles/2017/javascript-without-loops/">去掉循环</a>、<a href="http://jrsinclair.com/articles/2017/javascript-but-less-iffy/">写的更少</a>，不论是初入门的新人还是中高级工程师都建议阅读。好了，下面是本周精选的内容，React Native 比重较大，请享用。

### 文章教程

#### [箭头函数你需要知道的都在这儿了](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

箭头函数是 ES6 中的新特性，让函数代码更简洁，箭头函数本身没有绑定执行上下文，参数等等。很多时候，我们犯了错误才会明白“动手之前要先去看文档”，MDN 上关于箭头函数文档非常详细，关于哪里能用，哪里不能用，都解释的很详细，如果你就生在 ES6 的环境，这个必须得仔细看。

#### [写给略懂 jQuery 同学的 Vue.js 入门教程](https://medium.freecodecamp.com/vue-js-introduction-for-people-who-know-just-enough-jquery-to-get-by-eab5aa193d77)

jQuery 在前端领域的地位就像是 Web Server 领域的 Apache，据统计现在全球有 70% 的网站都引用了 jQuery，技术在进步，如果你只是略懂 jQuery 想学 Vue.js 咋办？学习新东西的最大障碍就是思维方式的转变，阅读这篇文章看看学会 Vue.js 接受哪些新的思考方式。

#### [通过案例学会 React Native Navigator  原理及用法](https://medium.com/react-native-training/react-native-navigator-navigating-like-a-pro-in-react-native-3cb1b6dc1e30)

React Native 入门的时候，脑子里面肯定很多疑问，React Native 里面是否有类似于 React Router 的东西？如果有怎么用？React Native 内置的 Navigator 就是用来干这个的，方便你开发多页面的 APP，这篇文章从最简单的例子开始教你如何使用 Navigator、传递参数、配置转场动画。

#### [管理 React Native 应用样式的几点建议](https://medium.com/@tommylackemann/managing-styles-in-react-native-3546d3482d73)

入手 React Native 开发的同学有没有纠结过应用的样式代码到底该放到哪里？是单独抽出来，还是全部内联？共享的样式怎么办？实际上没有标准的做法，这篇文章会给你一些建议，让你的代码更好管理。

#### [如何使用 HTTP Headers 来保护你的 Web 应用？](https://juejin.im/post/58f5d3718d6d810057c18f75)

无论是简单的小网页还是复杂的单页应用，Web 应用都是网络攻击的目标。开发者可以利用 HTTP 响应头来加强 Web 应用程序的安全性，通常只需要添加几行代码即可。本文将介绍 web 开发者如何利用 HTTP Headers 来构建安全的应用。虽然本文的示例代码是 Node.js，但基本所有主流的服务端语言都支持设置 HTTP 响应头，并且都可以简单地对其进行配置。

#### [大数据浪潮下的前端工程师](https://zhuanlan.zhihu.com/p/25825404?group_id=837335635386826752)

把前端工程师放在产业发展、技术进步的大背景下来审视，前端工程师不应该仅仅关注实现界面和交互，非常建议阅读，不多做解释。

#### [前端精读评论：前后端渲染之争](https://zhuanlan.zhihu.com/p/26366128)

十年前，几乎所有网站都使用 ASP、Java、PHP 这类做后端渲染，但后来随着 Angular、React、Vue 等 JS 框架的崛起，开始转向了前端渲染。从 2014 年起又开始流行了同构渲染，号称是未来，集成了前后端渲染的优点，但转眼间三年过去了，很多当时壮心满满的框架（Rendlr、Lazo）从先驱变成了先烈。同构到底是不是未来？自己的项目该如何选型？建议阅读

### 开发工具

#### [httpie: 比 curl 和 wget 更好用的网络工具](https://github.com/jakubroztocil/httpie)

httpie 是一款比 curl 和 wget 更好用的网络请求命令行工具，Egghead.io 上还有一门介绍 http 基础知识的免费课程全程就是用的这个工具，你看了这个课程 httpie 的用法和 http 基础都学会了，注意这个工具的读法是 “爱吃提提派”，而不是“爱吃踢踢屁爱意”。

#### [awaiting：async/await 辅助工具库](https://hunterloftis.github.io/awaiting/)

awaiting 是基于 async/await 特性的工具库，提供了常见的延时、等待，以及 Promise 相关的工具函数，想学好 async/await？看看先行者拿他做了啥会学的更快。

### 代码框架

#### [React Navigation：可扩展但易用的路由解决方案](https://github.com/react-community/react-navigation)

看了上面的 Navigator 文章，觉得他很难用，现在来看看 React Navigation，可扩展但非常易用的路由解决方案，由 Facebook、Expo、React 社区的共同努力演化而来，甚至可以用在 React 项目中。

#### [Split.js：轻量的视图分隔 JS 插件](https://nathancahill.github.io/Split.js/)

Split.js 是一款轻量级的视图（面板）分隔插件，无任何外部依赖，对 HTML 的书写也没有特别的规定，只需要分隔的面板有相同的父节点。支持横向、纵向分割，相邻的面板中间自动给加上了可拖拽的分割线。

### 找找灵感

#### [Froggy：玩儿游戏学会 Flexbox](http://flexboxfroggy.com/)

这样说吧，Flexbox 对布局带来的便利只有学会的人能真正体会到，这个 24 关的小游戏，通过灵活运用 Flexbox 把青蛙放到正确的位置，助你掌握 Flexbox 里面的各种属性用途、用法。

#### [漫画赏析：Linux 内核到底长啥样](https://zhuanlan.zhihu.com/p/26379813)

这篇文章为大家解读来自 TurnOff.us 的漫画 “InSide The Linux Kernel” ，非常形象有趣。TurnOff.us 是一个极客漫画网站，作者 Daniel Stori 画了一些非常有趣的关于编程语言、Web、云计算、Linux 相关的漫画。

### 视频教程

#### [Egghead.io：Redux 入门教程](https://egghead.io/courses/getting-started-with-redux?utm_content=bufferec33f&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

任何应用的状态管理都是至关重要的，Redux 被部分同学误解为是给 React 应用使用的状态管理工具，实际上他可以应用到更广义的 JS 应用中，本视频教程由 Redux 的作者（那个让 HMR（模块热更新）成为前端开发标配的男人）亲自录制，免费开放到了 Egghead.io 上，想学的赶紧去。

#### [JS 驱动网站的 SEO 最佳实践](https://www.youtube.com/watch?v=JlP5rBynK3E)

来自 Google 的工程师 John Mueller，跟大家分享现代网站（主要指大量使用 JS 网站） SEO 最佳实践，澄清了社区中关于 JS 网站 SEO 的一些认识误区，并给了不少有用的建议，需翻墙。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking
