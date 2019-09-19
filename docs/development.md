# 开发工作流规范 (基于 Git)

## 版本规范
前端项目使用[语义化版本](https://semver.org/lang/zh-CN/)进行发布，版本格式：**主版本号.次版本号.修订号**

版本号递增规则如下：
1. 主版本号：项目大版本改造，主版本号会迭代，比如开放平台二期、鹊台二期；
2. 次版本号：当开发一个 Redmine 常规需求时，次版本号升级；
3. 修订号：对已上线的分支，进行修复时，次版本号升级；

## 工作流规范
涉及多人并发协作，管理多个软件版本的情况下，定义良好的版本库管理规范，可以让大型项目更有组织性，也可以提高成员协作效率。

因为我们需要多人协作的方式，所以我们工作流是遵循的 Git-Flow；但是大部分团队会根据自己的情况制定自己的 Git 工作流规范，例如 Java 组的规范就跟前端组不一样。

所以我建议了解两种标准规范方式即可：
1. [Git-Flow 工作流](https://github.com/ivan-94/git-guide/blob/master/branch/feature.md)
2. [GitHub-Fork 工作流](https://github.com/ivan-94/git-guide/blob/master/branch/fork.md)

## 消息规范
我们严格准守 [AngularJS](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit) 提交规范。一个好的提交信息，可以提高项目的整体质量，所以至少具有下面这些优点：

- 格式统一的提交信息有助于自动化生成 CHANGELOG  
- 版本库不只是存放代码的仓库，它记录项目的开发日志，要清晰表达这次提交的做了什么。这些记录应该可以帮助后来者快速地学习和回顾代码，也应该方便其他协作者 Review 你的代码；  
- 规范化提交信息可以促进提交者提交有意义的。

下面这些工具可以帮助你检验提交信息和生成 CHANGELOG:
- [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) 从项目的提交信息中生成CHANGELOG和发布信息
- [commitLint](https://github.com/conventional-changelog/commitlint) - 检验提交信息
- [commitizen](https://github.com/commitizen/cz-cli) - 提交规范帮助工具

如果你遵循上面的规范，就可以利用[conventional-changelog-cli](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog-cli)来自动生成变更日志。

## 学习资料
[《Git Commit 标准化》](https://www.cnblogs.com/wubaiqing/p/10307605.html)



