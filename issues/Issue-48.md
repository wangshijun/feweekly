## 前端周刊第48期：Vue Conf 2017 + Progressive WEB APP

> 根据前端趋势观察，本期收录的内容有两个重点：Vue.js 周边，包括各种脚手架、工具库、技术交流大会；PWA 周边，包括视频、开发工具、应用示例。以下是具体内容内容，请享用！

### 文章教程

#### [PWA 在饿了么的实践经验](https://zhuanlan.zhihu.com/p/25800461)

本篇旨在和大家分享「饿了么 M 站」在 PWA 改造中的实践经验。涉及到的方面有：PWA 线上部署的准备工作、多页应用的 prerender 优化、实践过程中踩到的（和推进解决的）坑。而关于 PWA 的一些基础资料，可以看本周刊收录的其他资料。

#### [浅谈前端状态管理](https://zhuanlan.zhihu.com/p/25800767)

近两年前端技术的发展如火如荼，大量的前端项目都在使用或转向 Vue 和 React 的阵营，由前端渲染页面的单页应用占比也越来越高，这就代表前端工作的复杂度也在直线上升，前端页面上展示的信息越来越多也越来越复杂，任何状态都需要进行管理，这篇文章聊的就是前端状态管理，分上下两篇，下篇自己找。

### 开发工具

#### [TestCafe：现代 WEB 应用自动化测试利器](https://github.com/DevExpress/testcafe)

TestCafe 是纯 Node.js 编写的现代 Web 应用自动化测试工具，专用来进行 E2E 测试，不需要安装任何依赖就能自己启动浏览器、运行测试、收集测试结果，不需要任何插件就能支持各种现代浏览器，有人专门写了文章用它来测试 Vue.js 应用。

#### [pm86：生产环境的 Node.js 服务管理工具](https://github.com/ericjjj/PM86)

pm86 基于 pm2，类似于美团的 pm2.5，都是用来管理 Node.js 服务的工具，在命令行工具的基础上，提供了监控仪表盘，可以私有化部署，并且仪表盘使用 Vue.js 开发，如果你想定制也很容易。

#### [Eagle.js：基于 Vue.js 的 PPT 编写演示工具](https://zulko.github.io/eaglejs-demo/?utm_campaign=Revue%20newsletter&utm_medium=Newsletter&utm_source=revue#/)

Eagle.js 是一款基于 Vue.js 的 PPT 编写和演示工具，支持动画、自定义主题、可交互组件（非常适合在技术交流会上做 Demo 演示），并且能非常容易的实现组件、Slide、样式的重用。是个新轮子，并且还不是前端做的。

### 代码框架

#### [unvue：简单好用的 Vue.js 同构应用脚手架](https://github.com/egoist/unvue?utm_campaign=Revue%20newsletter&utm_medium=Newsletter&utm_source=revue)

支持服务端渲染的 Vue.js 同构应用脚手架，架构在具有强大的 SSR 能力的 Vue Router 之上。同时支持代码分割、Webpack 配置自定义、以及类似于 Next.js 的 插件机制。

#### [Vue.js 2 + Webpack 2 + TypeScript 2 应用脚手架](https://github.com/ducksoupdev/vue-webpack-typescript?utm_campaign=Revue%20newsletter&utm_medium=Newsletter&utm_source=revue)

如果你想用非常前沿的前端技术来开发 WEB 应用，这会是非常值得考虑的种子项目，内含 Vue.js 2.2、Webpack 2、TypeScript 2，支持热更新，工程化方面支持单元测试、覆盖率报告、静态资源编译和打包优化。

#### [Progressive Web App（PWA）版本的 CNode 社区](https://cnodejs.org/topic/58cd118bede0d3f7168541ef)

CNode PWA 是使用 React、React Router 和 Redux 构建的 Progressive Web App，基于 CNode 社区提供的 API 开发，对于在学习 PWA 的同学是个非常不错的学习材料。GitHub 首页支持扫码直接预览，可以直接安装到桌面，体验流畅。

### 视频演讲

#### [学习 PWA（Progress Web APP）的 10 段最佳视频](https://techbeacon.com/top-10-progressive-web-app-videos-get-speed-fast?utm_source=mobilewebweekly&utm_medium=email)

渐进式 WEB 应用，或者 Progressive Web App，亦被简称为 PWA，正被越来越多的开发者和互联网公司关注和讨论，因其基于现代的 WEB 技术，能够提供离线优先的、可以媲美原生的、轻量级 APP 体验。诸如 Google、Microsoft、Twitter 等大的互联网公司都在跟进。那么究竟什么是 PWA？开发 PWA 使用了哪些技术？需要借助什么工具？如果你想学，这 10 段视频就是为你准备的。

#### [像擎天柱变身那样转换代码：AST 入门指南](https://www.youtube.com/watch?v=WO7H2NHmN18)

有没有好奇 babel、less、sass、postcss 这些代码转换工具是怎么工作的？他们都有的一个机理就是 AST（Abstract Syntax Tree，抽象语法树），AST 是啥？有什么用？看看这段 48 分钟的视频，你就能理解清楚。需翻墙。

### 技术动态

#### [nginScript：在 Nginx 中使用 Javascript](https://www.nginx.com/blog/introduction-nginscript/)

Javascript 的使用范围真是越来越广，我们都知道 Nginx 脚本语言中 Lua 始终是不二之选，本周 Nginx 官方推出了 Javascript 支持，虽然和 Node.js 有区别，但是可以用 Javascript 在 Nginx 中干很多事情，比如请求处理、日志处理。

#### [npm 新功能：支持免费的机构账号](https://www.npmjs.com/features)

npm 本周宣布支持免费的机构账号，能省去不少自己造轮子搭建私有 npm registry
 的麻烦，免费机构账号的限制就是所有的仓库必须是开源的，免费版机构账号支持部分收费版的功能，比如组员管理。需要提醒的是这个就像是域名。

#### [Chrome 58 Beta 版发布：支持 PWA 全屏](https://blog.chromium.org/2017/03/chrome-58-beta-indexeddb-20_21.html?m=1)

Google 本周发布了 Chrome 58 Beta 版，其中包含了多个更新，如 IndexedDB 2.0、Iframe 导航的改进，亮点是支持 PWA 应用全屏。在我看来，PWA 跟微信的小程序是有异曲同工之妙，大的互联网公司都在布局，聪明的开发者该怎么做呢？

#### [VueConf 全球技术大会将于 5 月 20 在北京举办](https://zhuanlan.zhihu.com/p/25867191)

全球首届 VueConf 将于 5 月 20 日在北京举办，目前正在筹备过程中，近期会发布更多购票相关细节，感兴趣的小伙伴请保持关注了。同时，他们也在寻找讲师和赞助商。有兴趣有实力的公司或者朋友可以开始去原文联系举办方了。

### One More Thing

如果对文中的内容有任何疑问，欢迎留言讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/p/25644447)。

