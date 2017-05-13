## 前端周刊第55期：10X 程序员？

> 我本周读到 1 篇比较有趣的文章叫做《The 10x developer is NOT a myth》，不管你承不承认，也不管你有没有意识到，程序员的效率有时会有天壤之别，10X 程序员的概念很早就出现了，怎样才算 10X 程序员？跟普通程序员的区别在哪里？推荐你抽时间细读，如果你不愿意看中文，可以看看我写的《工程师做事的三重境界》。下面是本周精选的内容，请享用。

### 技术动态

#### [使用 Node.js 的那些理由还站得住脚么？](http://bysin.net/2017/05/07/no-good-reason-to-use-nodejs/)

技术社区的活力从各种撕逼的发生频率能看出来，这篇文章开头承认 Node.js 已经非常流行并且越来越流行，但是作者认为早些年列出的使用 Node.js 几大理由是站不住脚的，因为其他技术也在进步，在各个方面他们都比 Node.js 做的更好，你怎么看？

#### [ES6 模块加载登陆 Chrome Canary 60](https://medium.com/dev-channel/es6-modules-in-chrome-canary-m60-ba588dfb8ab7)

不知道 ES6 模块的同学应该去看看 Ponyfoo 或者 Jake 的文章，Chrome Canary v60 已经提供了 ES6 模块的支持，不过需要你手动打开支持。这篇文章可以说是新特性尝鲜文章，并且对如何开始在项目中使用这个功能、如何做恰当的回退都提出了可行的方案。

### 文章教程

#### [让无状态 React Component 渲染快 45% 的黑科技](https://medium.com/missive-app/45-faster-react-functional-components-now-3509a668e69f)

无状态 React Component 的概念就是那些纯粹负责渲染且没有状态变化的 Component，这篇文章的作者给出了让这类 Component 渲染加快的技巧：就是把它们当函数使、而不是当 Component 来使，如果你持怀疑态度，可以先看看他是怎么分析的，然后自己做实验来验证。

#### [从 Angular.js 到 Vue.js 的迁移之路](https://dev.to/hemantisme/moving-from-angular-to-vue--a-vuetiful-journey)

你的老系统是使用 Angular 1.x 开发，现在又不想使用变化太快的 Angular 2.x、4.x 版本？可以看看这篇文章的作者如何从 Angular 1.x 迁移到 Vue.js。

#### [玩转 React Native 动画所需要掌握的](https://medium.com/shoutem/declare-peace-with-react-native-animations-e947332fa9b1)

设计得当的交互动画能够让你的应用惊艳用户，使用户沉浸其中，典型的比如 Slack 的官方应用，作者在这边文章会跟你解释改如何去解剖一个动画（透明度、位置、尺寸、颜色），让你了解 React Native 动画的潜力，并且分享了如何设计能够使用到整个 React Native 应用中的动画的技巧。

#### [用 VSCode 做 React 开发推荐配置](https://hackernoon.com/configure-eslint-prettier-and-flow-in-vs-code-for-react-development-c9d95db07213)

与下面收录的 Atom 前端开发终极配置相呼应，这篇文章讲的是如何在 VSCode 配置好 ESLint、Prettier、Flow 以方便 React 开发，给目前在这个场景下的同学。

#### [用 Atom 做 JS/React 开发的终极配置](https://medium.com/productivity-freak/my-atom-editor-setup-for-js-react-9726cd69ad20)

虽然很多同学现在已经转向 Visual Studio Code 了，这个编辑器我也推荐，但对已经很熟 Atom 作为开发工具的同学这篇文章文章也不失其参考价值。怎么才算是完全掌握一个代码编辑器？把他当记事本用就行了？完全不是这么回事，你需要花时间去打磨和练习。这篇文章的作者花了几个月的时间把 Atom 的配置、插件、快捷键调到最优，可能不完全适合你，但是他的思路肯定是值得学习的。

### 开发工具

#### [Vim Awesome：非常棒的 Vim 插件站点](http://vimawesome.com/)

不是典型的 Awesome 清单，而是个独立的网站，收录了所有的 Vim 插件，做了分类，首页上能看到最受欢迎的 Vim 插件，使用 Vim 的同学请收下，使用其他 IDE 的同学请绕路，哈哈。

#### [Keycastr：小巧的按键可视化工具](https://github.com/sdeken/keycastr)

在你做技术演示、录制编辑器快捷键或者其他的 GIF 动图时，如果想全方位的把你的操作展示给观看的人，按键可视化必会让你的输出增色不少，Keycastr 是 Mac 下的一款按键可视化小工具，启动的时候会报错，你需要用管理员身份给他 Accessibility/Privacy 权限。

### 代码框架

#### [execa：一个更好的 Node.js child_process](https://github.com/sindresorhus/execa)

由在 npm 上发了 1000+ 个包的 Sindre Sorhus 出品，相比 Node.js 内置的
 child_process，这个会好用很多，主要的优点有：Promise 化、自动处理子命令输出结尾、比内置大 500 倍的输出 Buffer、更好的 Windows 支持、在父进程退出时自动清理子进程等，经常用 Node.js 来写脚本的同学可以考虑看看。

#### [BriteCharts：基于 D3.js 的图表绘制库](http://eventbrite.github.io/britecharts/)

BriteCharts 是一款基于 D3.js V4 版本的图表绘制库，研究过 D3 的同学可能都会觉得 D3 就是绘图领域里面的 DOM，直接使用它你的自由度更大，但是绘图成本相对更高。而 BriteChart 这样的库帮你封装了常见的图表，可以用非常直观的方式在页面中渲染。整个仓库使用 ES6 编写，并且测试覆盖率也非常好，源代码本身就是个不错的学习资源。如果寻找其他 D3.js 图表库的同学可以去搜搜 C3.js 和 NVD3.js。


### 视频教程

#### [基于 Chrome Dev Tools 的现代前端工作流](https://www.youtube.com/watch?v=v5r_n6Tq0uk)

Umar Hansa 在 Render Conf 2017 上所做的分享，主题是基于 Chrome Dev Tools 的现代前端工作流，里面的干货非常多，如果你想彻底掌握 Chrome Dev Tools，这篇绝对不容错过。内容涵盖：FPS Meter、Paint Profiler、Timeline Recorder、Source Code Profiling 等 15 个主题。

#### [egghead.io: 在生产环境中使用 Webpack](https://egghead.io/courses/using-webpack-for-production-javascript-applications?utm_content=buffer9fb7a&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

Webpack 无疑是前端社区中最受欢迎的 JS 应用打包工具，因为内置了太多的功能，它的学习曲线也非常的陡峭，让它跑起来就要费不少的功夫，跟别提用它来做更多的事情了，Kent C. Dodds 在这个系列视频教程中会用实例帮你理解 Webpack 最常用的功能，以及如何优化 Webpack 的配置让它跑的更快。

### 精彩问答

#### [如何让 Git 使用我最喜欢的编辑器？](http://stackoverflow.com/questions/2596805/how-do-i-make-git-use-the-editor-of-my-choice-for-commits)

对标题我先稍作解释，Git 的某些操作可能会打开系统中的某个编辑器让你填写内容，典型的就是 commit 的时候如果没指定 commit message，就会默认打开 VI 让你填写，如何把填写 commit message 的编辑器替换成我自己喜欢用的 Vim、Atom、VSCode？改下全局配置就行了，高票答案中有两个方案，要仔细看。

#### [做 React Native 开发时如何打日志？](http://stackoverflow.com/questions/30115372/how-to-do-logging-in-react-native)

打日志可能是众多调试手段中最古老，关键时候也最有效的手段，相比而言 React Native 开发时的日志打法有很多，你都用过哪些？哪些比较好用？看看这篇问答。

#### [真机调试 React Native 应用时打不开热更新？](http://stackoverflow.com/questions/38772373/how-to-enable-live-reload-in-ios-device-running-react-native-app)

可能部分同学遇到过，在真机调试 React Native 应用时，发现调试选项中并没有 Live Reload 和 Hot Module Reloading 的选项，这会对开发调试的效率产生很大的影响，问题产生的原因主要在网络，但是解决的办法超过 3 个步骤。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking
