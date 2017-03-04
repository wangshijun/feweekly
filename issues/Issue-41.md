## 前端周刊第41期

> 哈哈，内容周五已经准备好了，但是忘记点发送了，今早上发出，请享用~

### 文章教程

#### [手把手教你玩转 Github Pages](http://24ways.org/2013/get-started-with-github-pages/)

有人说 Github 就是工程师的简历，然而一图胜千言，在程序员的世界里，一个能运行的 Demo 胜过千行万行的代码和文档，相信不少同学有注意到很多 GitHub 上的仓库利用 GitHub 本身提供的功能能够展示 Demo，也有人利用 GitHub 搭建自己的免费博客，到底是如何做的？搞懂这些，详细你会更喜欢 GitHub~

#### [必读：可扩展 CSS 的方法论大搜罗](https://github.com/davidtheclark/scalable-css-reading-list)

该仓库围绕可扩展 CSS 这个主题的不少思路和解决办法，有些现在已经被广泛使用，比较有名的有 OOCSS、BEM、SMACSS 等，CSS 虽然简单，但是项目打了让你头疼的地方还不少，到这里来取取经吧，看看如何提高 CSS 代码的可维护性、可扩展性~

#### [论 Node 应用的持续部署](http://blog.risingstack.com/continuous-deployment-of-node-js-applications/)

自动化能给工程师节省非常多的时间和经理，这篇文章讨论持续部署需要解决的问题和好处，并且以 Node 应用为例说明~

### 开发工具

#### [SSHRC：带上你的终端配置去旅行](https://github.com/Russell91/sshrc)

喜欢用 Linux 命令行或者倒腾或服务器的同学肯定经常遇到需求，我 SSH 到陌生的远程机器，但是我很熟悉的 bash，vim配置都没有了，需要在那个机器上重新搞？有了 SSHRC，你就可以带上你的终端配置去旅行啦~

#### [MongoUI：类 phpMyAdmin 的数据库后台](http://webapplog.com/mongoui/)

MongoUI 是基于 Node 开发的类似于 phpMyAdmin 的 MongoDB 数据库管理后台，整体使用 BS 搭建，界面小清新，觉得在命令行中操作 MongoDB 很麻烦的同学快收下吧~

### 代码框架

#### [TableSaw：响应式表格插件合集](https://github.com/filamentgroup/tablesaw)

该仓库收集了很多响应式表格的 jQuery 插件，支持多种响应式表格的展示模式：比如单行变多行，表头选择，表格导航地图等等，做移动页面的东西可以看看，如果用不上，相信也能找找灵感~

#### [ACL：基于 Node 的权限控制组件](https://github.com/optimalbits/node_acl)

应用变大之后，自然免不了出现用户、角色之类的需求，伴随而来的就是权限控制的问题，同样的资源哪些人不能访问，哪些人能访问？ACL 对这块做了很好的抽象，可以很方便的指定角色的权限规则，并且支持多种会话存储方式，结合上 Express 和 Passport，相信能为你节省不少开发时间~

#### [Font Awesome Animation](http://l-lin.github.io/font-awesome-animation/)

利用 CSS3 让你的 Font Awesome 图标动起来，使用的是自己的 IconFont 库？没关系，学会他的实现思路就可以了~

#### [Hello.js：基于 OAuth 的浏览器端用户认证 SDK](http://adodson.com/hello.js/#hellojs)

开发浏览器端的单页面应用时常常会碰到接入各种第3放认证或者用户登陆的需求，比如 Google、GitHub、Twitter 等，每次都要去搜索这些 API 的文档，然后写大段的代码？Hello.js 把这些重复性的脏活累活帮你干完了，只需简单的 API 调用，遍能够快速实现各种第 3 方认证的接入，不过目前针对国内服务的插件还比较少，有兴趣的同学可以扩展~

### 视频演讲

#### [浏览器预加载机制探秘](http://www.slideshare.net/AndyDavies/london-web-standards-20140922-pdf)

了解浏览器的预加载机制么？为什么会存在这种机制？到底如何工作？看看这个演讲稿，你能了解个大概~

### 精彩问答

#### [Express：如何为路由增加命名空间？](http://stackoverflow.com/questions/17173286/how-to-mount-app-get-routes-on-a-particular-path-prefix)

Express 4 中对 Router 做了比较大的改进，可以为路由的 URL 增加命名空间了，浏览下这个问题的答案，你就知道具体怎么搞了~

#### [如何不用 Cookie 存储 GA 的数据？](http://davidmurdoch.com/2014/09/22/google-async-analytics-using-localstorage/)

用过 GA 的同学大概都知道，GA 对于 Session 的追踪是依赖 Cookie 的，这样产生的 Cookie 在你的主域上发生的每次请求都会带上，如果你的网站访问量很大，这个算下来还是个不小的带宽消耗呢，不光耗带宽，还可能影响网站性能哦，那么有什么优化办法？可以用 LocalStorage 存储这些数据，这篇文章指明了解决方案~

### One More Thing

想直接在微信中订阅前端周刊？扫下方二维码关注前端周刊订阅号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

每期的内容也会同步发送在前端周刊知乎专栏上：http://zhuanlan.zhihu.com/feweekly。

Happy Hacking
