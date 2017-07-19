# 前端周刊第60期：用空格缩进的程序员挣得更多？

> David Robinson 从 <a href="http://www.feweekly.com/contribution/2206">Stack Overflow 年度开发者调查</a>中发现的结论，使用空格缩进比使用制表符缩进的程序员平均年薪高 8.6%，即多超过两年的工作经验，当然这个结论是纯粹统计上的相关性，很难说就是实际的因果关系，最后作者特意强调为了薪水，他继续坚持使用空格缩进，你呢？

### 技术动态

#### [ CSS 年度调查报告](https://www.sitepoint.com/results-ultimate-css-survey-2017/)

Louis Lazaris 进行了为期 6 周的问卷收集，对 1600 份问卷结果做的汇总，基本覆盖了 CSS 社区今年以来发生的变化，比如比较受欢迎的工具、方法论、编码技巧，信息量不小。不论老鸟、新手透过这份报告能观察到大家都是怎么做的，不断打磨自己的工具箱长期来说会是非常划算的投资。

#### [TypeScript 2.4 RC 版本发布](https://blogs.msdn.microsoft.com/typescript/2017/06/12/announcing-typescript-2-4-rc/)

新版的 TypeScript 带来的特性包括：支持动态 import 表达式，更安全的回调参数检查，弱类型支持，字符串枚举等，其中弱类型支持是跟跟老版本不兼容的。正在学习或者使用 TypeScript 同学可以关注。

#### [V8 引擎发布 6.0 版本](https://v8project.blogspot.com/2017/06/v8-release-60.html)

这里探讨的 V8 引擎不是 Node.js 8，前段事件 Node.js 发布新版的时候，很多人把两者搞混了。该版本新增 SharedArrayBuffer 支持，并且带来了原生的 rest/spread 操作符支持。可用时间节点方面：V8 最新版将会在 Chrome 60 中发布，Node.js 也会跟随发布。

### 文章教程

#### [19 个常用的 JS 简写技巧](https://www.sitepoint.com/shorthand-javascript-techniques/)

用更少的代码做更多的事情，会让你成为更牛的程序员，说起来容易具体怎么做呢？熟练掌握代码的简写技巧就非常管用，作者在这篇文章中整理了 19 个常用的 JS 简写技巧，当然，部分简写转换是不等价的，注意原文中的标注，改出了 Bug 可不好。

#### [那些年处理过的内容溢出](https://css-tricks.com/handling-long-unexpected-content-css/)

靠谱的程序员会很在意自己写的程序的健壮性，弹 JS 的健壮性很好理解，实际上 CSS 也是有的，有没有这样的体会，设计图非常的完美，但是仅仅照着那个做出来的东西在生产环境数据的测试下可能出各种问题，其中最典型的就是内容溢出，这篇文章讲了不少内容溢出的处理办法，文末有彩蛋，有个叫做 ForceFeed 的工具帮你在开发阶段做内容溢出测试。

#### [代码讲解把 Console 用到极致](https://medium.freecodecamp.com/how-to-get-the-most-out-of-the-javascript-console-b57ca9db3e6d)

来自 FreeCodeCamp，Console 是多数程序员的调试首选，但 Console 对大多数人来说是既熟悉又陌生的，我亲眼见到不少新同学的调试代码写的很蹩脚，读完这篇文章，你能学到诸如如何用 Console 格式化输出、对代码计时、对输出分组、输出表格。

#### [高效 Node.js 程序员都有的开发习惯](https://blog.heroku.com/node-habits-2017)

这里整理了 8 个高效 Node.js 程序员都有的开发习惯，从包管理，到脚本管理，再到代码风格、测试等，原文用的次是 “Happy Developer”，养成这些好的习惯，能为你避免不少麻烦，麻烦少了，效率就高了，自然就会 “Happy”，不是么？

#### [Lin Clark：内存管理入门教程](https://hacks.mozilla.org/2017/06/a-crash-course-in-memory-management/)

程序员漫画作家 Link Clark 的作品，系列文章有 3 篇，链接在原文头部，即使初学者也能透过这 3 篇文章理解 JS 中为什么要引入 ArrayBuffer 和 SharedArrayBufer，以及引入这些特性之后如何处理特殊情况。

### 代码框架

#### [Awesome React Components](https://github.com/brillout/awesome-react-components)

有同学问我该怎么选择适合业务使用的 React 组件或者组件库，做任何选择的方法论都是相同的，先找到备选，然后添加必要的条件对备选进行过滤，关于 React 组件或者组件库，这篇就收录了不少备选，接下来的必要条件就跟实际的业务有关了。

#### [如何对 &#2489 这种文字解码？](https://github.com/mathiasbynens/he)

最近处理业务数据，发现部分数据全部被编码成了类似 &#2489 的内容，前端同学对这个应该都不陌生，因为 HTML 里面的 &gt; 和 &lt; 都是类似的，如何对这些东西解码？这篇就是个现成的轮子。

#### [React Native Spinner 工具箱](https://github.com/maxs15/react-native-spinkit)

Loading Spinner 是多数应用都会采用的交互方式，可以极大的减少用户感知的等待时间，这是把 spinkit 迁移到 React Native 的即插即用的组件，支持超过 10 种动效，相比内置的 ActivityIndicator 能给你更多的选择。

#### [Vue 专用 TypeScript 代码片段](https://marketplace.visualstudio.com/items?itemName=ducksoupdev.Vue2&utm_campaign=Revue%20newsletter&utm_medium=Newsletter&utm_source=revue)

如果想把 TypeScript 快速融入到自己的开发习惯中，需要找到很多类似的工具配置，这是专门为 Vue、Vuex 定制的 VSCode 代码片段，当然更好的方式是根据自己的工作方式去定制。

### 精彩问答

#### [Vim 如何实现无限撤销？](https://jovicailic.org/2017/04/vim-persistent-undo/)

Vim 如果不做任何配置，默认的撤销动作只能在当前打开的文件中执行，无限撤销的能力能让你撤销昨天甚至很久之前做的修改，只需要简单的几行配置就可以搞定。

#### [工作能力强的人有哪些共同特征？](https://www.zhihu.com/question/28880482/answer/176343416)

知乎上广受关注的问题，跟每个人的成长有关。你有没有在工作中遇到能力很强的人，不仅知识渊博，而且软实力让人佩服，做什么事情都感觉很让人放心。这类人有什么共同的特征？对我们有什么启发？

#### [如何优雅的杀掉卡住的 SSH 会话？](https://medium.com/fullwebio/how-to-kill-a-frozen-ssh-session-7c3da419d5f7)

遇到过 SSH 会话卡住的时候你会愤怒的敲键盘？粗暴的关掉终端窗口？实际上是有更优雅的方式来杀掉卡住的 SSH 会话，命令也很简单。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking


