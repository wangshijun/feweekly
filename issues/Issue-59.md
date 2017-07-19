# 前端周刊第59期：选 Flow 还是 TypeScript？

> 周末是时隔两月的家人团聚，而每次内容的准备平均需要我集中精力工作 3 小时，所以第 59 期的内容今早才准备好，对不住大家了。本期的引子是“选 Flow 还是 TypeScript”，缘起于去年底的 JS 调查报告展示 39% 的程序员听说过会准备采用 TypeScript，你是其中一份子么？从想用到真正开始用缺的就是实践。而笔者也是最近才开始拥抱 TypeScript。下面是本周精选内容，请享用。

### 文章教程

#### [架构师必读：开源软件的架构](http://aosabook.org/en/index.html)

英文系列名为《The Architecture of Open Source Applications》，这个系列文章强烈推荐有志于成为架构师的同学阅读，里面介绍了不少开源软件的设计理念，全套分四册，完全开源，覆盖的开源软件有上古神器，也有黑马新秀，如果你没有思考过这些司空见惯的东西到底是怎么设计的，相信这里面的文章会给你不少启发。最新的系列叫做《500 Lines or Less》，用 500 行代码能做什么？比较有意思

#### [util.promisify 用法详解](http://2ality.com/2017/05/util-promisify.html)

Node.js 8 增加的新特性，让你把各种基于回调的函数方便的转成 Promise，这样就可以在 async/await 上下文使用了，这篇文章介绍了基本用法。

#### [对比 Flow 和 TypeScript](http://djcordhose.github.io/flow-vs-typescript/flow-typescript-2.html#/)

主标题：JS 中的类型系统，原作者也是蛮拼的，JS 中类型系统的对比做了多次分享，早期对比了 Flow 和 TypeScript 1.x，后来对比了 Flow 和 TypeScript 2.x，最后还把 ELM 加入到对比里面。这是中篇的链接，对比的风格更学术化，如果你想对选用 Flow 还是 TypeScript 做出非常严谨的选择，这篇是不得不看的。

#### [从 Flow 到 TypeScript](http://jan.varwig.org/2017/02/15/flow-vs-typescript.html)

作者在使用 React 开发的早些时候，因为 TypeScript 还不够完善，遂全部采用 Facebook 开源的静态检查方案 Flow，时过境迁发现 TypeScript 更能满足需求，虽然标题里有 vs 字眼，但是明显倾向于 TypeScript，并且给出了从 Flow 到 TypeScript 的基本步骤。TypeScript 是 2016 年 JS 调查报告中 39% 的开发者听说过并且原因试用的技术，你还在徘徊犹豫么？

#### [React Native 渐进式图片加载思路](https://medium.com/the-react-native-log/progressive-image-loading-in-react-native-ecc88e724343)

WEB 和 APP 领域的很多东西都是通用的，对于多图的应用，图片加载的优化必不可少，这篇文章介绍了在 React Native 中实现图片渐进式加载的方案，并且有实际的代码示例。

### 开发工具

#### [Lighthouse：让 Dev Tools 如虎添翼](https://github.com/GoogleChrome/lighthouse)

Google 官方出品，目前已经内置在 Chrome Dev Tools 中，可以用来对你的网页，尤其是 H5 做全面的诊断，给出的报告涵盖 PWA、性能、可访问性、最佳实践等方面，不得不说，一份报告就有太多值得学习的地方。并且 Lighthouse 还提供了命令行工具，可以很好的与你的 CI 流程结合。

#### [ZangoDB：浏览器中的 MongoDB](https://github.com/erikolson186/zangodb)

ZangoDB 是基于 HTML5 中 IndexedDB 的类似于 MongoDB 的数据库封装库，如果你熟悉 MongoDB 的各种语法，那么在浏览器中书写 MongoDB 的代码来做数据过滤、分页、投影、排序、更新和聚合已经不是什么难事。

### 代码框架

#### [FastImage：高性能的 React Native 图片组件](https://github.com/DylanVann/react-native-fast-image)

这周对公司 APP 做图片加载优化，调研时找到了 CachedImage 和 FastImage，其中 FastImage 更新，但是允许开发者对图片加载的调度有更大的自主权，两者都支持 Placeholder、文件系统缓存。你可以根据自己的需要选用。

#### [FeatherIcon：美观的开源图标库](https://feathericons.com/)

社区中能找到的图标库越来越多，选择的时候你会考虑哪些要素？是否开源、图标的种类、版权、受欢迎程度、添加新图标的难度？Feather Icon 使用 MIT 授权，主维护者也比较勤奋，使用者不少，设计风格比较简洁，你也可以看看。

### 找找灵感

#### [学会做任何事情](http://www.wikihow.com/Main-Page)

你会教人如何使用筷子么？看起来很简单的事情，貌似找到他的关键，并且讲解给别人就没有那么容易了。wiki-how 里面有各种如何做 XXX 的教程，当你学一个新的东西时候，写个新教程的时候是不是可以参考呢？

#### [程序员应该访问的最佳网站](https://github.com/sdmg15/Best-websites-a-programmer-should-visit)

已经有人在掘金发过了，里面收录了程序员工作生活可能涉及到的各种网络资源的列表，比如怎么准备面试、去哪里看新闻、哪里有不错的视频教学、有哪些不错的 Youtube 频道、免费的编程书等等，如果你想练习提高自己的英文，这里的每个链接都可为你所用。

#### [动画渐变函数图示](http://easings.net/)

恰到好处的动画能让你的应用体验更加流畅，谈到动画，不得不提到渐变函数（即 easing functions），渐变函数基本决定了动画的视觉效果，每种不同的渐变函数到底是怎样的曲线？这里用图示法给你生动的解释。

### 视频教程

#### [学习 Recompose 中的高阶组件和函数式组件](https://egghead.io/courses/higher-order-components-with-functional-patterns-using-recompose)

来自 egghead.io，如果你使用了 React 相当长的时间，比如说一年，但是还不知道函数式组件、高阶组件是啥，这个视频教程当属于敲黑板系列了，如果说 《React Best Practice and Design Patterns》是文字版的，那么这个就是视频版的，虽然基于 Recompose 讲解，但是很多模式即使不用它也可以自己实现。

#### [egghead.io：60 分钟学会 ES6](https://egghead.io/courses/learn-es6-ecmascript-2015?utm_content=buffer6a6db&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

是 egghead.io 上为数不多的多人合作的视频课程，通过实际的编码演示了 ES6 中的各种新特性，如果你只是看了 ES6 的各种新语法、结构，但是还是羡慕别人的代码为啥写的那么溜，可以来看看这个，当然，最好的办法是自己跟着练。

### 精彩问答

#### [如何使用 Git 管理大文件？](https://medium.com/fullwebio/how-to-track-large-files-database-psd-bin-in-git-263aac9f93f2)

如何使用 Git 管理诸如 PSD、二进制文件、数据库文件等的大文件？这里给出了详细的步骤，有版本的东西就好追溯，软件演化周期的各种资源都是一样的，而 Git 在做这种记录的时候有着天然的优势。

#### [如何使用 JS 格式化货币数字？](https://stackoverflow.com/questions/149055/how-can-i-format-numbers-as-money-in-javascript)

可能不少同学会想到去找个库，如果你的需求很简单，何不自己尝试写个呢？这是个正则的解法，注意答案被讨论的比较多，谨慎采用（仔细看文档总是有好处的）。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking

