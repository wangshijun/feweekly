# 前端周刊第47期：Vue.js 后台模板 + React Conf 2017 + 饿了么面试宝典

> 本文共 2676 字，读完需 5 分钟，速读需 1 分钟。认真阅读每期推送的同学可能发现，前端周刊收录的文章很大比例是英文，早期甚至全是英文，后来接到很多同学反馈才适量增加了中文内容的比例。但是整体来讲，我期望能给大家一个刻意学习技术英语的机会，期望有心人能把握。另外，我上周翻译了<a href="https://zhuanlan.zhihu.com/p/25709238">《2016 年崛起的 JS 项目》</a>，同步发到了<a href="https://zhuanlan.zhihu.com/feweekly">知乎专栏</a>，建议打开这封邮件的同学都去阅读下，绝对会有所收获。

### 文章教程

#### [Vue.js 组件编码规范中文版](https://github.com/pablohpsilva/vuejs-component-style-guide/blob/master/README-CN.md)

早些时候，本周刊推送了 Vue.js 组件编码规范英文版，这篇是中文译本，英文不好的同学可以学习下，但是最终建议还是学好英文，可以先从翻译开始。

#### [使用 TestCafe 对 Vue.js 应用进行 E2E 测试](https://alligator.io/vuejs/e2e-testing-testcafe/?utm_source=javascriptweekly&utm_medium=email)

TestCafe 是 2016 年出现并且已经有不少人采用的 E2E 测试工具，追求软件质量的团队和开发者都会想办法给项目增加测试，测试因粒度不同可分为：单元测试、接口测试、集成测试，而 TestCafe 是用来做集成测试的，即前端说熟知的 E2E 测试，这篇文章介绍了如何使用 TestCafe 对 Vue.js 应用进行 E2E 测试。

### 开发工具

#### [goops：给仓库添加最佳 gitignore 规则的命令行工具](https://github.com/captainsafia/goops?utm_source=nodeweekly&utm_medium=email)

goops 能够给你当前的工作目录添加 .gitignore 文件的命令行工具，当然他实际上比这个更强大，goops 会分析你当前目录下的文件来决定忽略哪些文件，可以说具有一定程度的智能。

#### [完成 E2E 测试的 5 个最佳 Node.js 工具](https://medium.com/@adrian_lewis/top-5-most-rated-node-js-frameworks-for-end-to-end-web-testing-f8ebca4e5d44#.vk449a1r5)

这篇文章里面列出了适合用来对项目进行 E2E 测试 5 个最佳工具，其中就包括本期周刊收录的另外一篇文章《 使用 TestCafe 对 Vue.js 进行 E2E 测试》里面的 TestCafe，如何让前端的迭代更快、更有自信？调研下这些工具，挑选最适合你的。

### 代码框架

#### [Vue.js + Element UI 的管理后台模板](https://github.com/lin-xin/manage-system)

一个基于 Vue.js + Webpack + Vuex + Vue-Router + Element UI 的管理后台种子项目，相比饿了么官方开源的那个而言，可以说是专业版，对常见的管理后台功能做了增强，比如所见即所得编辑器、文件上传、主题支持等。

#### [Epilogue + Express + Sequelize 快速搭建 API 服务](https://github.com/dchester/epilogue)

使用 Express + Sequelize 搭建后端服务是比较常见的技术组合，如果架构是前后端分离的，就需要服务端暴露出各种 API，而 API 遵循某种规范是最好的做法，最常见的就是 Restful 规范了，Epilogue 就是这样的插件，帮你快速把 Express + Sequelize 的服务变成 Restful 接口，支持各种各样的定制。

#### [vue-moment：Vue.js 日期处理的 filter](https://github.com/brockpetrie/vue-moment)

moment.js 可以说是前端领域日期时间处理的标准库，在使用 Vue.js 开发应用的时候免不了要格式化日期，vue-moment 已经帮你把这个事情做了，直接引入，就可以在模板中输出变量的时候添加 moment 的过滤器。

### 找找灵感

#### [Gulp 优秀插件、文章、教程大合集](https://github.com/Platform-CUF/use-gulp)

这应该是除了 Gulp 官方的文档和教程之外最好的插件、文章、教程大合集，我比较好奇的是，为啥作者没有把这个仓库命名为 awesome-gulp，虽然 gulp 在前端社区里面的出现不算是早的，但是学会使用它绝对是值得的。

#### [Awesome Element：饿了么组件库周边](https://github.com/ElementUI/awesome-element)

又一张 Awesome List，围绕着饿了么大前端开源的 Element 组件库收集了不少的资料，不管是在使用、打算使用的同学都可以看看，从里面找找是否有可以用的轮子。

### 视频演讲

#### [React Conf 2017 视频大合集](https://www.youtube.com/playlist?list=PLb0IAmt7-GS3fZ46IGFirdqKTIxlws7e0)

本周结束的 React Conf 2017 上有相当多的干货，目前视频都在 Youtube 上放了出来，本届 React Conf 的内容也非常精彩，包括：Facebook 内部的 React Native 之路、React 同构应用、Redux 和 MobX 对比、React 开发工具、GraphQL、React VR 等，英语好的同学自行翻墙去学习。

### 精彩问答

#### [如何在 git-diff 中准确的展示改了哪个单词？](https://twitter.com/csswizardry/status/757592722479976448)

新版的 git 中提供了 --word-diff 的功能，对于写 Markdown 的同学非常有用，不同于传统的整行 diff 模式，他是按词语来进行 diff，让你更加清楚的看到道理改了哪个地方。当然，使用这个特性需要升级下 git 版本。

### 技术动态

#### [Guetzli: 谷歌开源了效率更高的 JPEG 图片编码算法](https://research.googleblog.com/2017/03/announcing-guetzli-new-open-source-jpeg.html)

Guetzli 是谷歌近期宣布开源的新的 JPEG 图片编码算法，在视觉无损的情况下，编码出来的图片体积能减少 20% ~ 30%，官方代码仓库、周边配套工具已经开始出现，想加快图片加载速度、节省带宽？赶紧用起来。

#### [GitHub：更新开源项目许可证的展示](https://zhuanlan.zhihu.com/p/25821233?utm_source=zhihu&utm_medium=social)

GitHub 更新了 License 界面，让你对 License 一目了然，如果项目是根据流行的开源许可证（如MIT，Apache或GPL）获得许可，您将看到许可证的简要说明，以及您可以和不能对项目执行的操作的概述。

### 职位招聘

#### [如何通过饿了么 Node.js 面试？](https://github.com/ElemeFE/node-interview)

这是饿了么官方整理的如何通过他们 Node.js 工程师面试的攻略，里面涵盖了用 Node.js 做服务端开发的几乎所有领域，能看的出来，整理这篇内容的人能力、视野都非常的强，即使你没在找工作，还有有很大的参考价值。

### One More Thing

如果对文中的内容有任何疑问，欢迎留言讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/p/25644447)。

