## 前端周刊第54期：Prepack 引发社区小高潮

> 你看到这篇文章的时候，在德国举行的，2017 年 <a href="http://2017.cssconf.eu/">CSSConf.EU</a> 和 <a href="http://2017.jsconf.eu/">JSConf.EU</a> 应该已经闭幕了，从推特上放出来的<a href="https://markdalgleish.github.io/presentation-a-unified-styling-language/">资料</a>来看，干货确实不少，好学的同学有这个信息应该就够了。Facebook 开源 JS 代码优化工具 Prepack 的事情貌似又引发了社区的一波小高潮，相信理性的你也有自己的判断。下面是本周精选内容，请享用！

### 技术动态

#### [Chrome Headless 终于来了](https://developers.google.com/web/updates/2017/04/headless-chrome)

Headless Chrome 在 Chrome 59 中已经可用，把 Chrome 的强大能力带到了命令行中，搞浏览器端持续集成和功能测试的同学可以上手玩玩了？这篇文章作为入门。稍微解释下 Headless 的概念，只需要通过命令行去访问，不需要用户界面的工具都可称之为 Headless，早期的 PhantomJS 就属于这种。

#### [Facebook 开源 JS 代码优化工具 Prepack](https://www.zhihu.com/question/59360593)

Facebook 近两月在开源领域动作频频，最近又开源了 Prepack：优化 JS 源代码的工具，实际上它是通过部分求值器（Partial Evaluator）在编译时执行原本在运行时的计算过程，并通过代码重写来提其执行效率。该怎么看待 Prepack？知乎上不少同学从不同角度发表了看法。

### 文章教程

#### [如何更好的组织 React 项目的代码？](https://medium.com/@alexmngn/how-to-better-organize-your-react-applications-2fd3ea1920f1)

项目代码的组织方式在很大程度上决定了新手上手项目的速度，项目后期的维护成本，基于代码角色（比如 component、container、action、reducer）的代码组织方式被很多人使用，也出现在很多脚手架工具中，那么这种组织方式到底适不适合项目的长远发展呢？从个人经验来说，基于业务领域的顶层组织可能更适合长远的可维护性。这篇文章给出了可行的代码组织建议。

#### [Nest：使用 TypeScript、面向对象和函数式变成写后端](https://kamilmysliwiec.com/nest-final-release-is-here-node-js-framework-built-top-of-typescript)

Nest 是一款使用 TypeScript 开发的 Node.js 框架，结合了面向对象和函数式编程的思想，基于 express 构建，对后端应用的结构做了更高的分层和抽象。你不一定需要使用，可以透过这篇文章看看它的设计思想。

#### [给 Node.js 新手：提高效率必备的工具和库](https://node.university/blog/725514/node-toolchain)

不少刚入门 Node.js 的同学可能都会问这个问题，新手该如何利用社区中的工具和库最大程度的提高自己的效率呢？JS 语言基础当然是不可少，因为如果你没有提高效率的基础知识，效率自然无从谈起。接下来就是工具和库的选择，要做到尽量少的浪费时间，这篇文章做了梳理，包括编辑器、代码库、命令行工具等几大类。

#### [关于监控的几个基础问题](https://mp.weixin.qq.com/s?__biz=MzA3MDMwOTcwMg==&mid=2650004810&idx=1&sn=0c22de4721d8f7c8118ba45e4a7bb6b1&chksm=8739bf63b04e3675ccd5e803e981fd0f188d25a247abad16692207a100eeaff3184895184bf2&mpshare=1&scene=24&srcid=05036Fr9uHOXKjccJHMdQ0zb&key=454f3c8ee53)

如果你觉得系统监控跟前端没啥关系，那就认识太局限了。页面的加载速度、JS 报错的数量趋势都是前端工程师应该负责的范畴，但是具体到监控，很多时候，做了跟没做一样，有时甚至都没做。介绍监控的常识问题，非常值得你阅读。

### 开发工具

#### [pkg：把 Node.js 应用打包成可执行文件包](https://github.com/zeit/pkg)

zeit.co 出品的命令行工具，帮你把 Node.js 应用打包成可执行文件，可以直接部署到任何环境，支持跨平台，没有 Node.js 运行时也是没问题的。基于他你把 Node.js 应用打包成安装包分发给客户。国内貌似阿里有实践，但是没有系统的开源出来。

#### [codecopy：让你成为更好的代码摘抄员](https://github.com/zenorocha/codecopy)

或多或少，我们都会从网页粘贴代码到自己的项目中，codecopy 是一款加速你代码摘抄过程的浏览器插件，在页面所有疑似代码片段的地方增加复制按钮，目前支持 Chrome、Firefox，支持的网站基本包括了所有程序员常去的网站，比如 GitHub、GitLab、Medium、NPM 等。

#### [create-next-app：快速开始 React + Next.js 项目](https://open.segment.com/create-next-app)

create-next-app 看名字就很像 create-react-app，能够快速的帮你开始一个 React + Next.js 的项目，Next.js 不多解释了。该命令行工具简化项目初始化之外，还提供了超过 10 个项目模板供你选择，比如你可以选择性的加入 Redux 或者 Mobx 等 React 全家桶玩具。

#### [AppiconMaker：帮你生成跨平台的应用图标](http://appiconmaker.co/)

AppiconMaker 是一款在线的图标缩放工具，你提供原图，它输出能直接导入到
Xcode 或 Android Studio 的不同尺寸的应用图标，如果想用离线版本，可以看看 makeappicon.com。

### 代码框架

#### [rn-splash-screen：用 JS 控制的 APP 闪屏组件](https://github.com/mehcode/rn-splash-screen)

APP 闪屏是 iOS 中率先使用的提高用户感知速度的设计，后来部分 APP 拓展了这个设计的外延，在启动的时候展示或者播放广告，在 React Native 中也是可以实现的，这个库同时支持 iOS 和 Android。

#### [react-native-masonry：灵活的砖块布局组件](https://github.com/brh55/react-native-masonry)

砖块布局（Masonry Layout）常用来展示多列的多图页面，在 WEB 端和 APP 端都比较常见，react-native-masonry 给你提供了可以直接在 react-native 中使用的组件，支持动态列、图片渐进加载以及事件绑定。

### 视频教程

#### [egghead.io：20 分钟掌握 async/await ](https://egghead.io/courses/asynchronous-javascript-with-async-await)

async/await 能让 JS 的可读性再上一个台阶，但实际使用中你可能还是会碰到不少问题，比如如何和匿名函数、箭头函数结合使用？多个 async 如何排列性能最好？花 20 分钟学习下这里的课程，或许你能发现自己之前的不正确用法。

### 精彩问答

#### [Git 如何提交只改了文件名大小写的变更？](http://stackoverflow.com/questions/17683458/how-do-i-commit-case-sensitive-only-filename-changes-in-git)

在对文件命名大小写不敏感的文件系统中，如果你改了文件名（只是大小写变化），Git 默认模式是识别不了这种变化的，自然就无法提交，那该怎么做呢？有不少方法，看看 StackOverflow 的讨论。当然绕过这个问题的办法是约定所有的文件名小写。

#### [如何知道仓库的代码行数？](https://zhuanlan.zhihu.com/p/26684427)

有句话，可能很多人忽略，但是却是个不争的事实：没有 BUG 的代码就是没有代码。优秀的工程师是能用更短小、简洁的代码写出相同的功能的，即使第一次没有写出来这种代码，他通过后续的重构也能达到，那么怎么跟别人证明重构能让代码变少呢？你需要一个计算代码行数的工具。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking
