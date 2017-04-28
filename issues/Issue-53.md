## 前端周刊第53期：React 社区的撕逼

> 本期有篇深度文章介绍 MobX，MobX 的原作者在 Medium 上有[个人频道](https://medium.com/@mweststrate)，写了至少 5 篇长文介绍自己的 React + MobX 心路。此外，[React Amsterdam 技术大会](https://react.amsterdam/#talks)已经闭幕，干货非常多，但需要你花较多时间去消化它的[视频](https://www.youtube.com/watch?v=m_vUUgI0bo8)。以下是本周精选内容，请享用。React 社区的撕逼接下来就是。

### 技术动态

#### [Facebook 官方回应社区对 React 的质疑](https://medium.com/@dan_abramov/hey-thanks-for-feedback-bf9502689ca4)

撕逼的事情在国内外都时有发生，本周 Medium 上有篇题为[《Things nobody will tell you about React.js》](https://medium.com/@gianluca.guarini/things-nobody-will-tell-you-about-react-js-3a373c1b03b4)的文章痛批 React，大意为：React 上手太困难，React Native 的 Issue 太多且没人处理，React 及周边工具版本迭代不向前兼容等问题。随后 React 官方维护者 Dan Abramov [发表长文回应](https://medium.com/@dan_abramov/hey-thanks-for-feedback-bf9502689ca4)，澄清了很多外界对 React 的误解。真理越辩越明，仔细看看两篇文章，相信你能收获不少。

### 文章教程

#### [React+MobX 组合与 Vue.js 的详细对比](https://github.com/jarsbe/react-vue-comparison)

React + Mobx 的组合和 Vue.js 在架构上基本是相同的，这篇文章对这两种技术做了比较细节的对比，还有具体的代码，后来附加上了 Preact 这个轻量级的替代。到底哪个好？没有最好的，只有合适的，只有知道各种技术的优缺点你才会做出更合理的选择。

#### [代码中添加注释之好坏丑](https://juejin.im/post/5902126aa0bb9f0065e80ea9)

有句经典：好的代码自身就是文档。在代码中添加注释有哪些禁忌，有哪些建议，掘金翻译计划已经为你准备好了。当然，如果想写出一手漂亮的代码，还是建议去阅读更有体系的[《The Art of Readable Code》](http://dl.finebook.ir/book/5f/14474.pdf)[彩蛋]，这本书也有中译本，但我强烈建议看英文。

#### [MobX 内部分治策略详解](http://divideandconquer.surge.sh/#1)

大多数同学认为 MobX 是为 React 定制的状态管理工具，这点不可否认，实际上它出现的比 Redux 晚，看到了 Redux 用在实际项目中会带来的问题，对现代前端应用中的 State、View 采用分治策略来击破，让开发者充分体会到响应式编程的好处。这个讲稿是 MobX 作者在 [React Amsterdam](https://react.amsterdam/#talks) 大会上的分享底稿，里面有 4 页能让你掌握 MobX 的思维模型。

### 开发工具

#### [styled-components：把 JS 中的 CSS 进行到底](https://github.com/styled-components/styled-components)

写 React 的同学肯定纠结过 CSS 该怎么组织的问题。传统 WEB 开发里面推崇的 CSS、JS、HTML 关注点分离不建议把 CSS 写到 JS 里面，随着开发方式的演化，这种写法总会让人觉得很别扭，因为从概念上来讲组件要具有封装、自治的特点，那么把 CSS 写到组件里面会更容易维护，也能把 JS 的功能发挥到极致，styled-components 就是这样一个库，让你很容的用 CSS 创建比较纯粹的样式组件，一旦你用上它，肯定会爱不释手，我就是这种感觉。

#### [lint-staged：只检查即将要提交的代码](https://github.com/okonet/lint-staged)

很多同学可能用过 npm 里面的 pre-commit 或者类似 husky 的工具来实现代码提交之前的编码风格检查，可有没有这样的痛点：你改了文件 A，但是代码检查工具提示你文件 B、C、D 里面都有不合规的地方，甚至问题还非常多，真是让人沮丧。lint-staged 能帮你只检查要提交的代码，而不是全量检查。

#### [TypeScript + Node.js 的 Yeoman 生成器](https://github.com/ospatil/generator-node-typescript#readme)

想使用 TypeScript 但是嫌工作流工具的拼凑过程太麻烦？可以试试这个 Yeoman Generator，能够让你快速开始使用 TypeScript 编写 Node.js 的包，实际上给浏览器编写也是可以的，生成的代码就包含了各种构建、测试的脚本，甚至还提供了 Visual Studio Code 的任务配置。

#### [Star History：GitHub 仓库发展史透视工具](http://www.timqian.com/star-history/)

基于 Star History 你可以查询任何仓库 Star 数量的变化趋势，有点类似于 Google Trends，但是基于 GitHub 官方 API 提供的精准数据。在你做技术选型、调研的时候可能会比较有用。

#### [TestCheck.js：让你的测试更健壮](http://leebyron.com/testcheck-js/)

请仔细思考这句话：测试只能让你发现 Bug 确实存在，但是不能帮你证明没有 Bug。通常来说，我们的测试只会测试最常见的情形，这样的话覆盖度自然就不是最高，而 TestCheck 能够帮你在测试的时候生成一些随机的输入，助你更早的发现潜在的问题。

### 找找灵感

#### [PWA 应用实例搜罗站点](https://twitter.com/Real_CSS_Tricks/status/857383799822229504)

这篇推文列出了三个搜罗 PWA 应用实例的站点，如果你在学习、研发 PWA，没有什么比生产环境的项目更具有研究价值了，可能都需要翻墙，自备梯子。

#### [Live：前端工程师的入门与进阶](https://mp.weixin.qq.com/s?__biz=MzI3MzQ0NjY4Mg==&mid=2247483740&idx=1&sn=f905f1d4a3457da99bf375d208dcd758&chksm=eb226329dc55ea3f508cdb333fab2e224261d9c3641d091c5637fe78477effc54be3aa0951f8&mpshare=1&scene=2&srcid=0423Mob2KnHfmHW7RXfxz2Ec&key=c78ef623e277)

justjavac 的知乎 Live：前端工程师入门和进阶，有知友整理出来了学习笔记，里面干货非常多，推荐给在前端路上狂奔的所有同学。

### 视频教程

#### [React Amsterdam 大会学习资料](https://react.amsterdam/#talks)

React Amsterdam 也是质量非常不错的 React 技术交流会，整体内容分为 React 和 React Native 两条主线，少数几个分享者还就相同主题在 React Conf 2017 上做了分享，大会在 Youtube 上有直播，自己去搜索就好，建议先仔细看看分享日程，然后在视频中选择性观看。

#### [React Native 经验分享](http://slides.com/windy/react-native-advanced-experience-by-80percent#/)

应该是不多的中文的 React Native 实战经验分享，介绍使用 React Native 的好处，使用的现状，踩到了什么坑，最后这部分是参考价值最大的，并且也是篇幅最大的，在使用或者学习 React Native 的同学建议看看。

### 精彩问答

#### [如何在 React Native 启用 ES7 Decorator 特性？](http://moduscreate.com/using-es2016-decorators-in-react-native/)

ES7 中的 Decorator 特性能让你少些很多重复的代码，写 React 的同学可能经常会碰到需要 bind 上下文的情形，这是用 Decorator 的绝佳场景，关于 Decorator，Google 的工程师 Andy Osmani 有篇经典文章[《Exploring EcmaScript Decorators》](https://medium.com/google-developers/exploring-es7-decorators-76ecb65fb841)。这篇文章给出了在 React Native 项目中启用 Decorator 的方法。

#### [Node.js 中的哪些库让你相见恨晚？](https://www.zhihu.com/question/24611701)

知乎上的一个问题，列举了不少使用比较多的库，不过个人觉得，最应该参考的是 npmjs.com 上被依赖最多的 package 列表，这个列表是全自动动态更新的，去哪里看？[猛击这里](https://www.npmjs.com/browse/depended)。

### One More Thing

如果觉得本文对你有帮助，请不要吝啬 star。如果对文中的内容有任何疑问，欢迎提 Issue 讨论。想知道我接下来会写些什么？欢迎订阅知乎专栏：[《前端周刊：让你在前端领域跟上时代的脚步》](https://zhuanlan.zhihu.com/feweekly)。或者扫描下方二维码订阅微信公众号。

![feweekly](http://www.feweekly.com/img/src/weekly/feweekly/qrcode.jpg)

Happy Hacking
