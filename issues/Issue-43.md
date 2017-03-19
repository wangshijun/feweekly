## 前端周刊第43期：前端工程师手册2017版

> 嘿嘿，本期开始前端周刊的内容会同步发布在名称都为《前端周刊》的微信公众号、知乎专栏、简书专栏上，欢迎大家根据自己方便的方式去订阅，邮件也会继续发送。下面是第 43 期内容，请享用！

### 文章教程

#### [前端工程师手册 2017 版](https://frontendmasters.gitbooks.io/front-end-handbook-2017/content/)

托管在 gitbook 上可以免费阅读的开源书籍，内容涵盖前端的基础知识，前端最佳实践，前端工作流，里面收录了非常全面的前端工程师工具，如果你想把前端功夫修炼的出神入化，这本书就是你的行动指南。

#### [Google Analytics 追踪脚本的正确使用姿势](https://philipwalton.com/articles/the-google-analytics-setup-i-use-on-every-site-i-build/)

相信不少前端同学或者站长都是用 Google Analytics 来追踪和分析自己网站的访客，如果你还仅仅是嵌入了官方提供的那一段代码，赶紧学习下这个吧，如何做 Google Analytics 做错误追踪、性能统计，甚至自动化事件发送。

### 开发工具

#### [vm2：更优秀的 NodeJS vm/sandbox 机制](https://github.com/patriksimek/vm2)

因为业务需要，研究了下如何在 NodeJS 中运行用户输入的代码，比如让他自己定义某个字段的计算公式，然后在业务后台根据这个计算公式去计算另外一个指标，发现了 内置的 vm 模块基本满足需求，本文的 vm2 更强大，支持模块导入、输出控制、代码预编译等特性。

#### [git-pr：管理 Pull Request 的小工具](https://gist.github.com/gnarf/5406589)

git-pr 是一个很简单的小工具，能帮你在管理 Pull Request 的时候去掉部分重复工作，比如 checkout 远程的 pr 分支，清理本地的分支等等。工程师的效率很大程度上取决于他用的工具，快用这个武装自己吧。

### 代码框架

#### [Awesome Angular 2+ Components](https://github.com/brillout/awesome-angular-components)

这是一篇 Awesome 系列仓库，里面收录了 50+ Angular 2+ 的组件，还做了详细的分类：涵盖样式、布局、交互组价、数据状态管理、性能、项目脚手架等，如果你是 Angular 的老用户，可以来这里开开眼，看是否在重复造轮子，是否有比你造的还好的轮子。

#### [React Native Hackathon Starter Project](https://github.com/dabit3/react-native-hackathon-starter)

React Native 的种子文件，里面包含文件组织方式，各种命令，集成了 React-Native-Element，支持 Android 和 iOS 平台，非常适合快速的开始 1 个 React Native 应用，他的起名就是为黑客马拉松准备的。对于公司级的项目，可以参考另外 1 个脚手架工具 ignite，自己去搜。

#### [Tether：精巧的网页元素定位库](http://tether.io/)

我首次注意到 Tether 是在浏览 Bootstrap 4 的网站发现的，Tether 是一款非常小巧、灵活、强大的网页元素定位库，调用的语法也非常的语义化，体积非常小，Bootstrap 都使用了，你应该也看看。

### 找找灵感

#### [Github：开源项目参与指南](https://opensource.guide/)

可以说没有 Github 就没有前端领域的蓬勃发展，目前大家所熟知的开源项目基本都托管在 Github 上面，那么如何参与开源项目？如何自己主导开源项目？如何写作？如何管控代码质量？如何运营开源项目社区？这些问题都在这份指南中有非常具体的指导。

#### [Cheat-Sheet：自定义浏览器资源调度行为的几种方式](https://twitter.com/addyosmani/status/743571393174872064)

可能不少同学听说过 preconnect、preload、prefetch、prerender 、dns-prefetch 这些名词，他们究竟是用来做什么的？有什么用？什么场景下适合使用？怎么使用？来自 Andy Osmani 的 Cheat Sheet 给你解释的一清二楚。

### 视频演讲

#### [React Native 最佳技术演讲视频合集](https://github.com/tiaanduplessis/awesome-react-native-talks)

又一篇 Awesome 系列文章，整理了很多 React Native 相关的视频，主题涵盖性能优化、技术决策，实现原理等，适合 E 文好且有时间慢慢消化的同学看。

### 精彩问答

#### [Base64 编码到底好还是不好？](https://csswizardry.com/2017/02/base64-encoding-and-performance/)

做过前端性能优化的同学可能都知道某些时候为了减少网络请求的数量，会把页面中内联或者 CSS 中需要的图片做 base64 编码，但是这样做到底好还是不好？如果不好，是因为什么原因？都做了非常详细的分析。

#### [为什么文件名要小写？](http://www.ruanyifeng.com/blog/2017/02/filename-should-be-lowercase.html)

文件名要小写的原因分析，仔细看看，或许能给你以后少挖些坑。来自阮一峰。

#### [如何避免 iTerm 中的 SSH 会话出现 broken pipe？](https://twitter.com/arrix/status/2386444332)

使用 iTerm SSH 链接到远程服务器，空闲几分钟之后你会发现，链接被自动断开了，需要手动重连。有没有自动化的办法保持会话是活动状态呢？答案肯定是有，这篇文章里面就有答案，配置非常简单。

### One More Thing

想直接在微信中订阅前端周刊？扫下方二维码关注前端周刊订阅号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

每期的内容也会同步发送在知乎专栏[前端周刊](http://zhuanlan.zhihu.com/feweekly)上。

Happy Hacking
