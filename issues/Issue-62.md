# 前端周刊第62期：学习学习再学习

> 腾讯前端技术大会（TFC）和全球技术领导力峰会（GTLC）都于上周闭幕，我翻看了下讲稿，有价值的参考还是不少，不过本周最推荐的部分还是《Learning How to Learn》这门需要你花时间去学习、掌握的课程。最近在招实习生，也收录了部分高质量的面试资料分享给大家。以下是本周精选内容，请享用。

### 技术动态

#### [全球技术领导力峰会 PPT 下载](http://gtlc.geekbang.org/#schedule)

学习新知、探索未知、提升自我是技术人的本能，而对技术领导者来说，技术之外，更是有着广袤的世界亟待探索。全球技术领导力峰会（GTLC）是由极客邦主办的技术领导人盛会，今年是第二届，主题为“探索圆外的世界”，邀请了互联网及传统行业的权威技术领袖分享他们关于技术、行业、商业、投资、领导力的实践与见解。有志于成长为技术领导者的同学可以细细研究下。

#### [腾讯 WEB 前端大会 PPT 下载](http://tfc.alloyteam.com/ppt.html)

腾讯 WEB 前端大会（TFC）2017 是由腾讯主办，广邀国内外的前端大牛，有著名流行框架的作者、知名前端书籍的作者、WEB 工程化方面的权威等。部分讲师是从腾讯上千名前端工程师中精挑细选的优秀高级工程师，内容不仅涵盖 WEB 新技术、Node.js、框架、工程化、 图形处理等前端前沿内容 ，还包含极致的性能优化、海量用户运营等具有腾讯前端特色的宝贵经验。没有去现场的同学，PPT 的学习不可错过。

### 文章教程

#### [前端框架发展简史](https://medium.com/this-dot-labs/building-modern-web-applications-in-2017-791d2ef2e341)

原标题为《Choosing a frontend framework in 2017》，实际上介绍了自 Backbone 以来，各种前端框架（Angular.js、Angular、React、Ember.js等）出现的背景及后来的演变路径，可见作者对于每个框架的特点都非常熟悉，文末有人问作者为啥没提到 Vue.js，作者的观点也比较明确：Vue.js 是个非常不错的框架，目前集成了大多数框架的优点，但是还没有创造出新的特性。

#### [你应该知道的 6 个 React Native 性能贴士](https://www.simplytechnologies.net/blog/2017/6/6/6-tips-you-want-to-know-about-react-native-performance)

React Native 本身性能是非常好的，但是代码写的不好也很容易出现性能较差的 APP，在 Android 上尤其如此，为什么会如此？写出高性能的 APP 有哪些坑要避开？这篇文章开局介绍了 React Native 的基本工作原理，然后给出了几条操作性非常强的建议，内容涵盖组件优化、动画、导航等。

#### [像产品一样打造样式规范](https://seesparkbox.com/foundry/style_guides_as_products?utm_source=CSS-Weekly&utm_campaign=Issue-271&utm_medium=email)

续前篇《想产品一样打造交付流水线》，原题为《Style Guides as Products》，很多同学都知道样式规范的重要性，部分公司制定了自己的样式规范，只有极少数公司的样式规范能真正落到实处，成为开发者主动拥抱和维护的项目。你有没有觉得这跟做产品很像，技术人的产品观可以体现在很多地方，这次你也跟作者一起思考下如何用产品思维来打造样式规范吧。

### 开发工具

#### [bundlesize：打包后代码体积的哨兵](https://github.com/siddharthkp/bundlesize)

bundlesize 是一个很容易与 Travis、Circle 等 CI 平台集合的工具，能够帮你检查项目打包后的代码体积，并标识在你的 Pull Request 里面，让开发者在把代码合入主干之前对代码体积的变化做到心中有数，配置仅需 2 步，诸如 preact、styled-components 这类的开源项目都在使用了。

#### [create-component-app：react 组件初始化工具](https://github.com/CVarisco/create-component-app?utm_source=reactnl&utm_medium=email)

高效的工程师都会重度使用命令行，使用 react 创建组件时你还在复制粘贴么？是时候换个新的姿势了，create-component-app 提供了可高度自定义的命令行式的组件创建方法，支持配置组件的名称、种类（如 class、pure、stateless）、样式写法。嫌这个命令太长了？去设置个 alias 不好么？

### 代码框架

#### [jsdiff：基于 JS 的文本比较算法](https://github.com/kpdecker/jsdiff)

这是基于 JS 的文本 diff 实现，diff 不仅仅在代码管理领域适用，比如 git，在文档管理领域也是使用的，比如 confluence wiki 的文档历史，在业务系统中甚至也是适用的，如果你想在业务系统中保存详尽的操作日志，即回答“谁在什么时间把什么字段从什么改成了什么这个问题的时候”你可能需要用到这个思路。

#### [frontexpress：浏览器里面的 express.js](https://github.com/camelaissani/frontexpress)

非常喜欢 express.js 里面的中间件开发模式？使用 frontexpress 在浏览器里面也可以写几乎相同的代码了，frontexpress 是轻量级的浏览器端路由管理工具，如果你不依赖任何框架编写代码，它会是个不错的选择。

### 找找灵感

#### [React Native UI Kitten：包含 40 个页面的参考项目](https://github.com/akveo/kittenTricks)

跟早些时候出来的 Vue.js 开发的高仿饿了么很像，几乎包含了现代 APP 应用会用到的所有界面，比如加载中页面、登录、注册、仪表盘、列表、详情等，基于 react-native-ui-kitten 开发，集成了 Google Analytics 和 react-navigation，刚入门 react native 的同学可以参考。

#### [lnxpcs：让你看起来更极客的设计](https://github.com/jstpcs/lnxpcs)

这个仓库收集了不下 50 个跟 Linux 有关的艺术设计，比如各种 Linux 发型版本、Shell 版本、只有技术人才能看懂的漫画等等，每个艺术设计甚至有对应的纪念衫可以购买，你有没有兴趣自己去印一件？

#### [作为程序员的我年轻时犯的错](https://dev.to/miqubel/mistakes-i-made-as-a-developer)

十年互联网老兵的呕血总结，拉长了时间跨度的经验总结显得弥足珍贵：不要局限于一个平台、一门语言；不要为了钱去追求管理岗位；腾出时间放空自己；持续编码；积极参与社区等，对于刚入行或者入行几年的你是否有启示？

#### [最佳前端面试问题梳理](https://performancejs.com/post/hde6d32/The-Best-Frontend-JavaScript-Interview-Questions-%28written-by-a-Frontend-Engineer%29)

面试对于技术人，尤其是刚入门的技术人来说尤其重要，这篇文章道出了面试的基本框架，考察概念、编码、Debug、设计能力，对时下比较常被问到的前端面试题提出了自己的看法，并且给出了不少的比较有意思，我也时常在用的问题，如果你正在准备实习或者找工作，可以参考。

### 视频教程

#### [Learning How to Learn：元认知能力提升必学课程](https://www.coursera.org/learn/learning-how-to-learn)

个人非常喜欢的 Coursera 课程，主要内容是学习和认知的客观规律：你能透过这门课程看清人是如何学会一门新技能；为何花了很多时间学习大脑却感觉一团浆糊原因。不得不说；人的大脑和思维方式有哪些天生的缺陷，改如何避免。在这样一个知识爆炸的时代，你更应该需要掌握如何学习的底层方法。

### 精彩问答

#### [漫画：什么是动态规划？](https://mp.weixin.qq.com/s?__biz=MjM5OTA1MDUyMA==&mid=2655438647&idx=1&sn=4634f712fa4d0236aba60b8e8b7cc2cb&chksm=bd730b408a048256f204695598c0e4f74e75c9582f5b9c740057a69747b306de1a4c308d5388&mpshare=1&scene=1&srcid=0702N84baxNAmMFheg6Ck26Z&key=238113c46368)

走台阶问题的动态规划解法是很多大科技公司面试的时候会问的，你当时都答上来了么？这篇文章用比较生动有趣的方式介绍了什么是动态规划，动态规划的基本要素有哪些，怎么用它来解决简单的问题和复杂的问题。

#### [怎样花两年时间去面试一个人？](https://mp.weixin.qq.com/s?__biz=MjM5ODIzNDQ3Mw==&mid=2649967341&idx=1&sn=e23064e6a95385141b57449c98cc80e2&chksm=beca3aeb89bdb3fda2e5075b986170cf189c9f76e9e1c9dcce5798ac815b3fc4761c529402a5&mpshare=1&scene=24&srcid=07026xj7NPo0eI2IG7CCxYc2&key=e0f557c9f11)

Joel Spolsky 曾经感叹：招聘难，难于上青天，再难的问题也是有办法的，作者在本文给出了一个比较独特的招聘思路，基于书单和 GitHub，花费两年去面试一个人，虽然我们公司没有完全照这个实践，但是看不看书，GitHub 的代码在评估候选人的时候都是会综合考虑的。如果还没写多少代码，这篇文章的书单对你来说会是个不错的资源。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking

