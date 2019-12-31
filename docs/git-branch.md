# 项目分支规范

#### 项目中统一使用 git flow 作为分支规范管理工具

### 1、feature 分支

feature 分支名一般情况下要使用 redmine 号，举例：

```sh
$ git flow feature start R1234
```

如果有其它情况，比如优化，更新库，改版等可以使用具有一定描述的分支名+自己的姓名，举例：

```sh
$ git flow feature start optimise_shop_xiaoming
```

### 2、release 分支

release 分支名需要指定版本号，版本号需要根据发版的情况而定：

1. 大版本：x.0
2. 中版本：x.x.0
3. 小版本：x.x.x

举例：

```sh
$ git flow release start 3.0
$ git flow release start 3.12
$ git flow release start 3.13.5
```

release 分支在 finish 后，打的 tag 要跟分支名的版本号一致。

### 3、hotfix 分支

hotfix 分支名是小版本号+指定日期，举例：

```sh
$ git flow hotfix start 4.12.1.20191212
# 如果当天涉及多次改动，那么要在日期后面加上改动的次数
$ git flow hotfix start 4.12.1.20191212_2
```

hotfix 分支在 finish 后，打的 tag 要跟分支名的版本号一致。


