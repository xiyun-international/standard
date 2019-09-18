# 开发工作流规范 (基于 Git)

## 版本规范
前端项目使用[语义化版本](https://semver.org/lang/zh-CN/)进行发布，版本格式：**主版本号.次版本号.修订号**

版本号递增规则如下：
1. 主版本号：项目大版本改造，主版本号会迭代，比如开放平台二期、鹊台二期；
2. 次版本号：当开发一个 Redmine 常规需求时，次版本号升级；
3. 修订号：对已上线的分支，进行修复时，次版本号升级；

## 版本控制系统规范
涉及多人并发协作，管理多个软件版本的情况下，定义良好的版本库管理规范，可以让大型项目更有组织性，也可以提高成员协作效率。

因为我们需要多人协作的方式，所以我们工作流是遵循的 Git-Flow；但是大部分团队会根据自己的情况制定自己的 Git 工作流规范，例如 Java 组的规范就跟前端组不一样。

所以我建议了解两种标准规范方式即可：
1. [Git-Flow 工作流](https://github.com/ivan-94/git-guide/blob/master/branch/feature.md)
2. [GitHub-Fork 工作流](https://github.com/ivan-94/git-guide/blob/master/branch/fork.md)



