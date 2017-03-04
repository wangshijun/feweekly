## 前端周刊第44期：JS 新概念词典、TypeScript 免费好书、SHA1 可被破解

> 哈哈，从本周开始，我会每周翻译一篇精彩的英文文章同步发布到<a href="https://zhuanlan.zhihu.com/feweekly">知乎专栏</a>和微信公众号上，以照顾前端初学或者英文不好的同学。下面是本周的精彩内容，请享用。

### 文章教程

#### [JS 新概念词汇释义：第 1 部分](https://auth0.com/blog/glossary-of-modern-javascript-concepts/)

前端技术的发展和其他领域工程思想的引入，不少新词汇产生了，比如纯函数、非纯函数、函数副作用；函数式编程、响应式编程；不可变数据类型；高阶函数等，不少现代 JS 框架的设计思想都或多或少有这些概念在里面，这篇文章深入浅出的跟大家解释了每个概念是什么含义，英文不好的同学别担心，我会陆续把这篇文章翻译成中文发布在我的<a href="https://zhuanlan.zhihu.com/feweekly">知乎专栏</a>上。

#### [用户认证令牌你必须知道的 10 件事](https://auth0.com/blog/ten-things-you-should-know-about-tokens-and-cookies/)

随着 SPA （单页应用）的盛行，不少前端同学可能都会接触到基于令牌（Token）的用户认证机制，但是关于 Token 的各种细节你是否都了解的非常清楚？比如怎么存储？怎么刷新？怎么鉴权？跟 Cookie 和 Session 相比有啥不同？英文不好的请稍后，这篇文章我翻译后会发布在知乎专栏上。

#### [HTTP 2：现实世界的性能测试和剖析](https://css-tricks.com/http2-real-world-performance-test-analysis/)

也许你听说过 HTTP 2，他不是一个概念，现在很多云服务商、CDN 厂商开始支持支持这种新的网络协议，很多人都说 HTTP 2 理论上性能高很多，但是没有拿出实际的数据，这篇文章做了些实际的测试，结果应该是很有说服力的。

#### [免费好书推荐：TypeScript 入门教程](https://ts.xcatliu.com/introduction/hello-typescript.html)

作者是好朋友刘易成，从 JavaScript 程序员的角度总结思考，循序渐进的理解 TypeScript，原名《From JavaScript to TypeScript》，作者希望分享学习的过程，帮助大家更容易的理解 TypeScript。内容比较易懂，正在学习 TypeScript 的同学请收下。

### 开发工具

#### [oh-my-zsh：Github 上排名第 1 的程序员生产力工具](https://github.com/showcases/productivity-tools?s=stars)

oh-my-zsh 是社区驱动的 zsh 插件管理框架，目前有 1000 多贡献者，支持各种各样的插件（400+）和整体自定义，能够让你在命令行中把生产力提高到极致，如果你还没开始拥抱命令行，还在等什么呢？

### 代码框架

#### [Rock：来自人人车前端的 JS 全栈脚手架](https://github.com/renrenche/rock)

Rock 是人人车前端团队这一年多来前后端分离路上探索、积累出来的 JS 全栈脚手架，使用 webpack 作为打包工具，打包过程做了详尽的调优，后端基于 express，前端支持各种主流前端框架：vue、react，上手简单，文档详尽，开发者友好，并且主维护者是个大美女哦，感兴趣的可以去看看。

### 找找灵感

#### [笑喷：中国程序员容易发音错误的单词](https://github.com/shimohq/chinese-programmer-wrong-pronunciation)

有没有发生过这样的事情：跟同事讲了好多遍一个单词，但是还是没听懂，最后竟然是你的单词发音和他不同？这里收录了不少中国程序员容易发音错误的单词，你应该去看看，不懂音标的自觉去找老师。

### 精彩问答

#### [有哪些老鸟程序员知道而新手不知道的小技巧？](https://www.zhihu.com/question/36426051)

同样是知乎上的一个问题，回答里面有道有术，道是别人踩了很多坑总结出来的经验，而术是别人发下的能瞬间提高效率的奇技淫巧，里面肯定有你不知道的。

#### [大公司里怎样开发和部署前端代码？](https://www.zhihu.com/question/20790576)

文绉绉的说法就是大公司的前端团队如何交付产品，很多前端刚入门的同学可能要很久才能搞明白的事情，不少大公司的人来作答，建议仔细看，自己画图。

#### [链接跳转时 document.referer 什么时候会被置空呢？](http://stackoverflow.com/questions/19455450/document-referrer-empty-when-navigating-from-external-url)

我们都知道从页面中的链接或者JS触发的跳转，不论是外部还是内部，新打开的页面都会有 document.referer，但是某些情况下，浏览器处于安全考虑会把这个设置为空，比如从 https 协议跳转到了 http 协议。

### 技术动态

#### [TypeScript 2.2 发布日志](https://blogs.msdn.microsoft.com/typescript/2017/02/22/announcing-typescript-2-2/)

给没听过 TypeScript 的同学解释下什么是 TypeScript，他弥补了 JS 的弱类型缺陷，支持各种新的 ES 语法，并且能编译成高性能的 JS 代码去运营，目前发布了 2.2 版本：引入 object 类型，增强了对编辑器的支持。

#### [SHA1 加密算法被证实可破解](https://auth0.com/blog/sha-1-collision-attack/?utm_source=notifications-chrome&utm_medium=sc&utm_campaign=notifications)

MD5 被证实可以破解之后，部分同学建议转向 SHA1，认为他更安全，但是现在谷歌证实 SHA1 也能够被破解，即提供两份不同的文档，经过复杂的计算能产生相同的 SHA1，不过实际破解需要的时间长达 6500 年，对于大家来说安全问题可能还不是迫在眉睫，但是随着计算机性能的不断提升，未来肯定会是问题。

#### [Node.js v7.6 发布啦](https://mp.weixin.qq.com/s?__biz=MzAxMTU0NTc4Nw==&mid=2661157442&idx=1&sn=d5fb19edc2f421cbc13f6a432f2279e6&chksm=80d5d796b7a25e80223e3508e46d3cc699d49e909a17ed1f65f263cf30e8acdf08e105a14e33&scene=0&key=ab8bb8f63a4fc57b41b672577be9e96518dfd29992a47dfe447ca)

本次版本升级的要点包括：集成 v8 5.5 版本；支持 async 函数，再也不用加 flag 才能运行了；性能提升，尤其是内存，最多 35% 的提升；在 v8 5.7 对 async 函数的优化会有 4 倍以上的提高。感谢 i5ting 的翻译。

### One More Thing

想直接在微信中订阅前端周刊？扫下方二维码关注前端周刊订阅号。
![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)


想和我面对面交流？扫下方二维码添加我为好友。

![wangshijun](http://www.feweekly.com/img/src/weekly/feweekly/wangshijun.jpg)

Happy Hacking
