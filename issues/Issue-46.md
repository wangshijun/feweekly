## 前端周刊第46期：Vue.js、Visual Studio Code、程序员防骗指南

> 本期内容中 Vue.js 和 Visual Studio Code 的内容比重偏大，关注我知乎专栏的同学可以从我接下来的发文中找到原因，我每周会发布 1~2 篇高质量的技术文章到<a href="https://zhuanlan.zhihu.com/feweekly">知乎专栏</a>，欢迎大家订阅。以下是本期内容，请享用。

### 文章教程

#### [从零开始构建 JavaScript 技术栈](https://github.com/pd4d10/js-stack-from-scratch)

这是 JavaScript Stack from Scratch 的中文版，由我们团队高级前端荣剑同学翻译成中文：这是个简单直接的 JavaScript 技术栈构建指南。在此之前，你需要掌握基本的编程知识和一些 JavaScript 基础。本教程旨在将所有现代 JS 技术栈结合起来使用，并为每个工具提供最简单的示例。你可以把它当作从零开始编写代码样板的示范。

#### [你不得不知的 package.json 常识](https://nodesource.com/blog/the-basics-of-package-json-in-node-js-and-npm?utm_source=nodeweekly&utm_medium=email)

可以说 package.json 是整个 npm 社区和生态的核心要素，你可以认为他是包、模块的规格说明，其中的字段都是什么含义，应该如何使用，懂了这些，你的 Node.js 才算是入门。

#### [基于 Loopback 开发一个完整的 Rest API Server](https://blog.optis.be/developing-a-complete-rest-api-with-loopback-a3190edc105a#.qgjfxjwww)

Loopback 非常适合用来开发 API Server，他独有的 API Explorer 能够让你直观的了解系统所提供的所有接口，需要的参数。这篇文章教你基于 Loopback 开发一个完整的露营预定服务端，从脚手架到数据校验、安全、存储都有涉及。

### 开发工具

#### [husky：把 githooks 集成到你的工作流](https://github.com/typicode/husky)

husky 和 ghooks 类似，能帮你把各种检查真正的落实到代码提交和推送工作流，安装使用非常简单，非常多的开源项目在使用它做简单的质量控制。

#### [Visual Studio Code 的奇技淫巧](https://github.com/Microsoft/vscode-tips-and-tricks)

微软官方整理的，Visual Studio Code 的各种技巧，覆盖的面还比较广，包括快捷键、插件安装、主题设置、编程字体等。

#### [Awesome：Visual Studio Code](https://github.com/viatsko/awesome-vscode)

Visual Studio Code 在国外的开发者群体中已经非常的受欢迎，它的智能感知功能更是让很多工程师爱不释手，极大的提高了开发效率。这又是个 Awesome 仓库，里面整理了把 Visual Studio Code 编辑器发挥到极致需要的各种配置、插件。

#### [legit：快速为你的代码添加版权头](https://github.com/captainsafia/legit?utm_source=nodeweekly&utm_medium=email)

说程序员是天生懒惰的动物，一点不假，legit 就是这样的一个工具，能快速的为你的代码添加版权文件头，让你不能费劲的去复制粘贴。

### 代码框架

#### [flatpickr：简洁的轻量级日期时间选择器](https://github.com/chmln/flatpickr)

开发大型 WEB 应用少不了会有日期时间选择的交互，flatpickr 是一款扁平化设计的，现代简约风格的日期时间选择器，代码无依赖，体积相比 Bootstrap 和 jQuery UI 的那套小了不止一点点。

#### [SQLite Parser：JS 实现的语法解析器](https://github.com/codeschool/sqlite-parser)

sqlite-parser 是基于 peg.js 实现的兼容 sqllite 3 语法的解析器，简单的说就是能把 sql 语句解析成现成的语法树，有个这东西你能做很多事情，比如在人人车，我们基于他做了非常灵活的业务配置系统。

#### [iView：高质量的 Vue.js UI 组件库](https://www.iviewui.com/)

iView 是 一套高质量的 Vue.js UI 组件库，纯国产，相信国内的同学用起来会非常顺手，近期发布了 V2 版本，其中包含了命令行工具，能快速开始新项目。至于组件库的构成就不多说了，不输入社区中其他的组件库，甚至更丰富。

### 找找灵感

#### [基于 vue2 + vuex 构建的有 45 个页面的大型单页面应用](https://github.com/bailicangdu/vue2-elm)

基于 vue2 + vuex 构建的有 45 个页面的大型单页面应用，初学入门的同学接触最多的的是各种 hello world 程序，而 bailicangdu 花了两个月时间用 vuejs 几乎把饿了么的页面写了个遍，正在学 vue.js 的同学可以研究研究。

### 技术动态

#### [Safari 终于支持 performance timing](https://twitter.com/webkit/status/839540260111593472)

Safari 的最新技术预览版已经开始支持 performance timing，这对那些使用 performance timing 采集性能数据的同学来说，是好消息，因为这部分用户的数据采集不再需要 hack 了。当然目前是还在技术预览版中，不久之后才登陆正式版。

#### [Chrome 开发者工具可以贴在屏幕左侧](https://twitter.com/addyosmani/status/838782825994182656)

有没有因为 Chrome 开发者工具的面板只能贴在屏幕的右边或下边而感到不顺手？好消息是最新版的 Chrome 开发者工具支持把面板贴在屏幕左侧了，可以更新尝鲜。

### 职位招聘

#### [程序员找工作黑名单，已惊呆](https://github.com/shengxinjing/programmer-job-blacklist)

首先承认这不是招聘贴，说实话看到这个的时候我也笑喷了，不过每隔一段时间网上就会爆出程序员因跟老板不和并且利益没有保障的案例，有心人很快就整理了这个：程序员找工作黑名单，换工作和当技术合伙人要谨慎，希望对各位能有帮助。

### One More Thing

如果对文中的内容有任何疑问，欢迎留言讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/p/25644447)。
