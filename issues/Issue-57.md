## 前端周刊第57期：《战争与和平版》的 CSS-IN-JS 黑历史

> 不知道大家是否注意到，社区中出现的 CSS 尤其是 CSS-IN-JS 风格的轮子轮子越来越多，这个事情在前端社区引发的很多的讨论，或者说是争吵，比如有人说 CSS is Broken，就有人对 CSS is Fine。Cristiano Rastelli 以《战争与和平》为蓝本<a href="http://t.cn/RS2n5zl">回顾了历史</a>，也给出了非常赞的观察视角，程序员应该务实，而不是教条，更重要的是保持好奇心。

另外第 56 期提到的各种技术大会，已经陆续有人整理适合 WEB 的视频列表，本期收录了我看过的比较精彩的两个，如果你有时间看更多，请移步：<a href="http://t.cn/RS2nt5p">Google I/O</a>、<a href="http://t.cn/Ra1A2h7">JS Conf Europe</a>、<a href="https://vue.w3ctech.com/">Vue Conf</a>。

以下是本周精选内容，请享用。

### 技术动态

#### [NPM 5.0 发布：更像 Yarn](http://blog.npmjs.org/post/161081169345/v500)

官方的 NPM 5.0 发布日志，你需要知道的版本更新要点：更快，有 Benchmark 表明它比 Yarn 还快；能够自动保持 package.json 里面的缩进；--save 变为默认参数；支持离线模式；支持依赖锁定。官方源上面还只能安装到 4.6.1 版本。

#### [styled-components 2.0 发布](https://medium.com/styled-components/announcing-v2-f01ef3766ac2)

对，就是以抹指甲油图片为图标的那个 CSS-IN-JS 库，我第一次使用就爱上她了，本周发布了 2.0 版本，可以说是真正意义上的大版本，代码体积更小、添加 SSR 支持、发布全新的文档站点、新增多个 helper 函数帮助你实现代码复用、新增 Babel 插件来优化生产环境的代码，最重要的点是你可以直接升级到版本 2.0 而不用做任何更改。

#### [Autoprefixer 7.0 发布](https://evilmartians.com/chronicles/autoprefixer-7-browserslist-2-released?utm_source=CSS-Weekly&utm_campaign=Issue-266&utm_medium=email)

可能部分同学对 Autoprefixer 比较陌生，是能够自动帮你提高 CSS 的浏览器兼容性CSS 预处理工具，各种构建工具都有对应的插件。初版于 4 年前发布的，作者重写整个仓库（从 Coffee 到 Babel）之后，最近发布了 7.0 版本，新版最大变化是升级 BrowserList 到 2.0。

### 文章教程

#### [Stack Overflow 全站切换 HTTPS 之路](https://nickcraver.com/blog/2017/05/22/https-on-stack-overflow/)

本周宣布帮助 100W 开发者成功退出 Vim 的程序员社交网站 Stack Overflow 最近宣布了另外一件大事：花了两年时间终于把全站切换到 HTTPS，对于部分正在升级到 HTTPS 或者想升级的同学可以看看，有个心理准备。内容比较全面，从基础设施的迁移、到应用架构、代码逻辑的迁移，都有经验和教训。

#### [JS  函数的前世今生](https://bocoup.com/blog/the-many-faces-of-functions-in-javascript)

函数是 JS 中的一等公民，语言在进化，其中函数的编写、使用方式也在不断进化，这篇文章做了非常不做的梳理和讲解，从早期的函数表达式、函数声明，函数构造，匿名函数，到后来的箭头函数、generator、async 函数，以及不同语法组合的函数，值得看看。

#### [保障 CSS 编码风格的工具链](https://css-tricks.com/enforcing-css-syntax-style/?utm_source=CSS-Weekly&utm_campaign=Issue-266&utm_medium=email)

清晰简洁的代码看起来养眼，读起来也更易懂，在 JS 领域，有很多工具来保障编码风格，比如 ESLint、Standard，也有工具帮你格式化代码，比如 Prettier、JS-Beautify。社区还比较年轻的 CSS 领域呢？早期的 csslint 太难用，但是最近一两年出现了几个比较好的工具，比如代码检查的 stylelint，代码格式化的 stylefmt。

#### [Style Guide Guide：编写样式规范的指南](http://bradfrost.github.io/style-guide-guide/)

比较重视代码重用和用户体验一致性的前端团队在处理复杂的业务都会着手积累自己的样式规范，但实际操作过程中，可能部分样式规范后来沦为纸上的规范，该如何维护真正有价值的样式规范呢？比如样式规范该怎么组织？文档该怎么写？向 Brad Frost 学习。

### 开发工具

#### [sitespeed.io：给你的应用来个全面的性能诊断？](https://www.sitespeed.io/)

sitespeed.io 完全基于开源工具构建，能够一键对你的 WEB 应用做全面的性能诊断，内涵 Browsertime、ChromeHar、PageXRay 等工具，支持把结构输出到 Grafana，安装方式也比较灵活，近期在关注性能的同学可以看看。

### 代码框架

#### [Shoutem 开源的 React Native 动画组件](https://github.com/shoutem/animation)

Shoutem 已经被认为是移动领域的 WordPress，可以快速帮用户构建 APP，其在 React Native 上做的事情还是不少，这是他们开源 React Native 的动画组件，支持常见的位置、大小、透明度、坐标轴，动画作者还在 Medium 上发了一篇不错的文章：《Declare Peace with React Native Animations》，感兴趣的可以去搜来读读。

#### [在 Node.js 顶级作用域中直接使用 await](https://github.com/robertklep/top-level-await)

或许你也曾疑惑，为啥 Node.js 里面的 await 语法不能直接使用，而需要在特定的 async 函数中使用，这个 package 源自 Sindre Sorhus 在 twitter 发的一条牢骚，实现的方式也比较 hack，很可能这个特性会出现内置的支持，梦想是要有的，万一实现了呢。

#### [ensure-error：确保你收到的是 Error 对象](https://github.com/sindresorhus/ensure-error)

npm 社区贡献的各种 package 在数量上绝对碾压其他语言，但是质量也是参差不齐的，具体到笔者自己踩过的坑就是某些包抛出的错误不是标准的 Error 实例，导致我们的错误处理代码要做特别的改造才不会在处理错误的时候再出错。和 ensure-callback 类似，这个包能确保你拿到的 error 是正确的对象，Sindre Sorhus 这种发现问题解决问题的思路非常值得我们学习。

### 找找灵感

#### [Awesome 系列：函数式编程的资料合集](https://github.com/xgrommx/awesome-functional-programming#javascript)

Awesome 系列，整理了函数式编程方面的很多不错的演讲、文章、视频，覆盖的语言也比较多，感兴趣的可以慢慢看。

### 视频教程

#### [DevTools: State of the Union 2017](https://www.youtube.com/watch?v=PjjlwAvV8Jg)

由 Paul Irish 在 Google I/O 2017 上给大家带来的分享，里面包含大量 Chrome 开发者工具的现场演示，比如：调试 PWA 的功能和技巧；如何解读应用性能、可用性报告；如何使用最新的 async 单步调试功能；如何快速的在开发者工具中编写、保存代码。

#### [WebAssembly 对 React 究竟意味着什么？](https://www.youtube.com/watch?v=3GHJ4cbxsVQ)

程序员卡通作家 Lin Clark 在 JSConf EU 2017 上的演讲，Facebook 是真心想把 React 的性能做到机制，而 WebAssembly 确实快，二者结合起来会怎样？我不剧透了，感兴趣的自己看哈。如果想看 Link Clark 的更多卡通画，可以去搜 ”A Cartoon Guide to“。

#### [egghead.io：玩转 JS 中的数组](https://egghead.io/playlists/learn-javascript-arrays-in-depth-dbe40331?utm_content=buffer4b7ca&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

数组可以说是任何编程语言里面最重要的数据类型，JS 也不例外，掌握他们的必要性不必言语，该视频列表涵盖了几乎所有的 JS 数组操作，内涵不少使用数组完成常见任务的特别技巧。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking
