# 技术栈规范

开发效率是基于稳定且熟练的技术栈，它有利于团队协作和沟通。我们对新技术是完全开放的，新技术、新的解决方案，是为了提升更高的生产力而诞生的。

我们容纳一个新的技术选型会有以下几点考虑：
- **学习成本** 考虑团队成员的接纳能力。如果成本小于收获的利益，在团队里面推行估计阻力会比较大，比如 pug；
- **收益** 是否能够解决当前某些痛点；
- **考虑风险** 我们不会将一个 Beta 阶段的技术使用的生产环境中；

## 语言
后续的语言选择，跟随着 Vue 逐渐迁移到 TypeScript。

## 框架
项目是基于 [Vue](https://cn.vuejs.org/v2/guide/index.html) 框架进行开发的，UI 统一使用 [Ant-Design-Vue](https://vue.ant.designh) 为了提升开发时的效率，我们还根据 UI 的不同，自研了 [禧云生态](https://xiyun-international.github.io/xy/) 公共组件库。

## 样式
- 编码风格规范，主要使用的是 [Airbnb](https://github.com/airbnb/javascript)；
- 语法检查要通过 [ESLint](https://eslint.org) 的验证；
- 方法的命名规范，遵循 [Clean Code Javascript](https://github.com/ryanmcdermott/clean-code-javascript) 标准；
- 项目的代码需要使用 [JSDocs](http://www.dba.cn/book/jsdoc/) 注释规范；
- CSS 的命名规范，遵循 [BEM](https://en.bem.info/methodology/quick-start/)；预处理器统一用 [Less](http://lesscss.cn/)。

## 测试
项目的测试工具，使用 [vue-test-utils](https://vue-test-utils.vuejs.org/zh/)，具体使用方式，参考 [Jest](https://jestjs.io/docs/en/tutorial-react) 官方指南。

## 项目管理
依赖管理工具，使用 [Yarn](https://www.yarnpkg.com/zh-Hans/)，组件开发与维护需要使用多包管理工具，[Lerna](https://github.com/lerna/lerna)。

