## 前端周刊第63期：前端新手如何快速提高？

> 本周 <a href="http://2017.jsconf.cn/">JSConf China</a> 于上海闭幕，掘金和知乎上都有对应的<a href="https://juejin.im/post/5969821851882534a31cab5b">实录</a>和<a href="https://www.zhihu.com/question/62154473">问答</a>，但会议的 PPT、视频目前都还没放出来，有心的同学如果找到了欢迎分享。最近公司入职了 3 个实习同学，关于实习同学如何快速掌握熟练工程师的工作流程、开发套路来自我提升本期收录多条精彩内容。以下是精选内容，请享用！

### 技术动态

#### [ES8 发布及主要特性总览](https://hackernoon.com/es8-was-released-and-here-are-its-main-new-features-ee9c394adf66)

ES8 已经正式发布，这篇文章使用实例对 ES8 中确定的语言特性（比如 Object.values、Object.entries、String.padStart、String.padEnd）做了介绍，基础好的同学可以自己去阅读规范原文，此外，掘金翻译计划也把文章翻译成了中文。

### 文章教程

#### [JS 项目行军指南](https://github.com/wearehive/project-guidelines)

对于相当比例的工程师，尤其是刚入门的前端工程师来说，开始一个全新的项目就像是在未知领域摸索前行，如果方法不当，维护老项目更是噩梦，那么推进新项目是否有固定的套路可循呢？这篇文章是 Hive 的团队总结出来的 JS 项目行军指南，覆盖了 Git、依赖、测试、文件组织、代码规范等方面。

#### [API 安全检查清单](https://github.com/shieldfy/API-Security-Checklist)

《清单革命》中提出在医学领域使用检查清单是保障复杂手术成功简单却有效的方法，有人把这种方法论迁移到建筑领域，而软件工程领域同样使用，对于开始接触 JS 后端开发的同学，如何保障 API 服务的安全有很多方面需要考虑，如果想让自己成为思维缜密的工程师，这篇文章及其中提到的概念和技术，非常值得学习。

#### [awesome-guidelines：编码风格指南](https://github.com/Kristories/awesome-guidelines)

高质量的代码会体现在表层和结构两方面，表层主要指代码排列、变量命名等方面，结构主要体现在容错、扩展、调试等方面，表层的代码技巧相比结构方面更容易掌握，而通常来说表层很差的代码，结构也好不到哪里去，这篇汇集了很多门语言的编程规范、最佳实践。

#### [每个单元测试都必须回答的 5 个问题](https://medium.com/javascript-scene/what-every-unit-test-needs-f6cd34d9836d)

有个难以接受但是残酷的事实，大多数程序员都不知道怎么写测试，测试不仅能帮助你理清对需求的理解，还有利于设计的开展，更直接的是方便持续集成为以后的自动化回归打好基础。那么该怎么写测试？正确的思考都是从提问开始，每个单元测试都要回答 的问题包括：你在测什么？它是干啥的？输入是什么？输出是什么？如何重复测试？

### 开发工具

#### [Release：快速生成仓库的 Changelog](https://github.com/zeit/release)

Zeit 官方发布的命令行工具，运行之后能自动生成 GitHub Release，并且基于上次发布之后的提交生成本次 Release 的更新日志，如果不了解这种发版流程，建议去看看 React、React Native 的版本更新机制。

#### [Chrome 60 DevTools 新功能预览](https://www.youtube.com/watch?v=Qnmb2YhkQmQ)

Chrome 无疑是配备了最好的开发者工具的浏览器，该视频通过实际操作讲解 Chrome 60 中新发布的 DevTools 功能，感兴趣的可以看看。

### 代码框架

#### [Gifted Chat：React Native 会话式 UI 库](https://github.com/FaridSafi/react-native-gifted-chat)

在 AI 时代，人机交互的方式也有不少新的变化，具体到前端领域，会话式UI（Conversational UI）的崛起尤为显著，微信公号上的自动回复功能也可算作此类，Gifted Chat 是为 React Native 定制的会话式交互组件，在交互细节上做了不少的优化考量，也支持灵活的自定义，如果你最近想做个类似的 APP，应该可以用上。

#### [franc：支持超过 800+ 语言的语种检测库](https://github.com/wooorm/franc)

如果你恰巧也需要在工作中处理多国语言，而需要知道数据库中存储的文本语种，franc 绝对能为你所用，支持超过 800+ 语种，支持计算某段文本属于某种语言的概率，长的文本输入能给你更精确的结果。

#### [Markvis：在 Markdown 中输出图表](https://github.com/geekplux/markvis)

不得不说 Markvis 为 Markdown 带来了更加丰富的表现力，支持条形图、饼图，并且这种需求是刚需，在 Markdown 越来越普及的今天。

### 找找灵感

#### [Practical Node.js：第2版](https://github.com/azat-co/practicalnode)

Practical Node.js 开始修订第 2 版了，预计年底会完工，这个仓库是手稿原文，如果你看过的话是不是也可以参与进去呢？该书的第一版< href="https://www.amazon.com/Practical-Node-js-Building-Real-World-Scalable/dp/1430265957/ref=sr_1_1?ie=UTF8&qid=1500419270&sr=8-1&keywords=practical+node.js#customerReviews">评价还比较不错</a>。

#### [VimGameSnake：在 Vim 中玩贪吃蛇](https://github.com/johngrib/vim-game-snake)

代码写累了想在 Vim 里面休闲下？请收下这款游戏吧，不要跟老板说是前端周刊介绍的，哈哈。当然，如果你想在 Vim 中尝试更多的游戏，可以移步：github.com/jmanoel7/vim-games。

#### [AI 术语中英文对照表](https://jiqizhixin.github.io/AI-Terminology-page/)

如果你知道某个领域各种术语对应的英文单词，能看懂英文技术资料就会更容易，前端为什么要关注人工智能？科技发展的趋势是挡不住的，即使不做人工智能的开发，多学点单词也能避免不少拼音式变量名吧。

### 精彩问答

#### [如何对压缩混淆后的 JS 代码做逆向工程？](https://www.alexkras.com/reverse-engineering-one-line-of-javascript/)

很多前端同学在初入门的时候可能都用到了逆向工程的方法，区别就是逆向的难度大小的问题，通常 CSS、DOM 再明显不过了，你对压缩混淆过的 JS 代码做过逆向工程么？没有的话，读读这篇长文，看看 Alex Kras 是如何做到的。

#### [为什么 Reddit 选择了 TypeScript？](https://redditblog.com/2017/06/30/why-we-chose-typescript/)

Reddit 的前端团队在做重构的时候重新选择了 TypeScript 作为基本的开发语言，他们调研了哪些方案？选择 TypeScript 的理由是什么？如果你时间有限就看最后的结论吧。

#### [认真的 JS 开发者必须知道的 10 件事？](https://www.reddit.com/r/javascript/comments/6mlc9d/what_10_things_should_a_serious_javascript/)

由一个想提高自己的前端工程师发布在 Redit 上的问题，高票答案总结的非常不错，现在的前端工程师跟五年前的前端工程师已经大不相同，如果你想在这个领域立足并成为大牛，这个答案可以作为基础技能检查清单。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking

