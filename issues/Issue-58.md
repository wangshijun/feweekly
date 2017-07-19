# 前端周刊第58期：送你 3 道面试题

> 破解前端面试系列文章本周出到第 3 篇：<a href="https://zhuanlan.zhihu.com/p/27172276">如何搞定纸上编程环节</a>，早些时候发布了<a href="https://zhuanlan.zhihu.com/p/25855075">闭包篇</a>、<a href="https://zhuanlan.zhihu.com/p/26420034">DOM 篇</a>，感兴趣的同学可以看看，对面试官和求职者都应该有些参考价值，每篇文章下面的讨论也是值得阅读的，部分读者提出了非常不错的建议和想法。下面是本周精选内容，请享用。

### 技术动态

#### [Prettier 发布 1.4.0 版本](https://github.com/prettier/prettier/releases/tag/1.4.0)

非常好用的代码格式化工具 Prettier 本周发布了 1.4.0 版本，新版增加了对 CSS、Less、SASS、TypeScript 的支持，也修复了格式化 JSX 时的一些问题，预计接下来各代码编辑器插件也会紧跟升级，VSCode 里面的插件已经升级完了，你还在等啥？

#### [CSSConf EU 2017 视频列表](https://www.youtube.com/watch?v=-9lhH72KlKY&list=PL37ZVnwpeshF0XmpjKBJ3-0kvr3b5ZpJR)

原计划收录在 56 期的技术大会视频里面的内容，但是考虑到信息量太大，延迟到了这周。这是 CSSConf EU 2017 的视频列表，相比而言 CSS 的社区更小也更年轻，但是还是有不错的内容，跟 CSS-IN-JS 有关的题为《A Unified Styling Language》演讲推荐观看，Medium 上也为相同名字的文章。

### 文章教程

#### [JS 模块现状和建议](https://medium.com/webpack/the-state-of-javascript-modules-4636d1774358)

最近关于 Node.js 中如何实现 ES 模块的讨论多了起来，这篇文章对 ES 模块当下的发展做了梳理，包括各种工具（比如 Webpack、Rollup）的支持情况，浏览器的支持情况。并在最后就是否应该开始 ES 模块给出了比较中肯的建议。

#### [阅读 flexbox 规范学会的 11 个要点](https://hackernoon.com/11-things-i-learned-reading-the-flexbox-spec-5f0c799c776b)

作者阅读了 flexbox 的规范之后，对 flexbox 又有了更深的理解和认识。作者感慨，通过阅读规范，它最大的收获是知道自己原来对 flexbox 的理解是不完整的，即使他看了很多博客文章，写了不少代码。技术深度就是这样练出来的，比如你是否有看过 es5、es6 的规范呢？

#### [你应该知道的 5 个 Node.js 8 新特性](http://codingsans.com/blog/node-8)

小有争议的一篇文章，介绍了 Node.js 8 里面你可以上手即用的 5 个新特性，关于 Node.js 8 的内容已经非常多了，大家可以自己去找，官方的发版建议阅读。

#### [O(logn) 时间复杂度到底该怎么理解？](https://hackernoon.com/what-does-the-time-complexity-o-log-n-actually-mean-45f94bb5bfbf)

算法时间复杂度里面的 O(1)、O(n) 等都是非常直观且容易理解的，可能你能意会 O(logn) 的复杂度，怎么跟人解释清楚？这篇文章的作者用图解法做了尝试，试试看？

#### [LeetCode 题解：免费电子书](https://www.gitbook.com/book/siddontang/leetcode-solution/details)

电子书的作者为了撬开算法的大门，刷完了 LeetCode 的题目，将自己做题的思路记录下来，教是最好的学，如果你最近正巧在刷题，会是不错的参考资料。

### 开发工具

#### [stylefmt：自动化的 css 格式化工具](https://github.com/morishitter/stylefmt)

stylefmt 是专门为 css 定制的格式化工具，支持 less、sass，也有插件支持各种新的 css-in-js 写法，比如 styled-components，周四我正好在项目中有实践，接下来会单独写篇文章解释如何把样式格式化工具集成到开发交付工作流中。

#### [chrome dev tools 性能工具大观](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/reference)

Google 官方出品的 dev tools 性能工具详细介绍，文章比较长，介绍了几乎所有 dev tools 内涵的性能工具，包含如何打开、录制，如何解读结果，发现问题，如果你真的想学会性能诊断，把这个加到学习列表吧。

### 代码框架

#### [react-native-animatable：超赞动画库](https://github.com/oblador/react-native-animatable)

高仿 animate.css，但是专门为 react native 定制， 各种动画都定义成了组件，动画声明方式也都是声明式的，参数可以直接通过节点 props 来控制。

#### [mocka：通用的内容占位符组件](https://github.com/Chalarangelo/mocka?utm_campaign=explore-email&utm_medium=email&utm_source=newsletter&utm_term=weekly)

内容占位符已经被越来越多的应用开始使用，不管是 APP 还是 WEB，掘金的 WEB 版就有，其作用就是提高用户对 APP 响应速度的感知，mocka 封装了常见的内容占位符代码，你可以直接在自己的项目中使用。不要看错了，这个是 mocka，和测试框架 mocha 仅一字之差。

### 视频教程

#### [用 tmux 管理你的命令行会话](https://egghead.io/courses/wrangle-your-terminal-with-tmux)

在程序员的世界里命令行终端就像是 chrome，会根据需要开很多个窗口或者标签页，但是机器重启之后如何快速恢复之前的工作目录，打开的文件，运行的程序？早些时候你可能需要用 screen，后来出现了更好的窗口管理工具 tmux，这个视频教程能让你在 30 分钟快速入门 tmux。

#### [如何禁用 react-native 中的黄色告警？](https://egghead.io/lessons/react-disable-and-ignore-yellow-box-warnings-in-react-native?utm_content=bufferdbed7&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

开发 react-native 的同学可能有注意到偶尔会遇到黄色的报警，每次刷新都会出来，有些你不打算处理的其实是可以用一行代码直接忽略掉、或者全部禁用（个人不推荐后面这种做法），egghead.io 的视频手把手的教你配置。

### 精彩问答

#### [react-native 中如何管理静态资源？](https://willowtreeapps.com/ideas/react-native-tips-and-tricks-2-0-managing-static-assets-with-absolute-paths/)

webpack 里面一切皆模块的思路同样可以用到 react-native 里面的静态资源管理，不过方法略有差异，比起在 react jsx 代码中零星分布的动态 require 更优雅。

#### [如何用 CSS 对图片裁剪和缩放？](https://stackoverflow.com/questions/493296/css-display-an-image-resized-and-cropped)

使用 CSS 对图片进行裁剪和缩放是实际业务中比较常见的需求，解决方法也不少，来自 Stack Overflow 的问答。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking

