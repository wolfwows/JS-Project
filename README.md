# -JS-
巩固JS相关的技术和相应的知识点，同时实现开发过程中的一些技术支持

插件一：日期格式化

正式开始

还不是道做些什么？

## 拉取指定分支代码解决方案：

以拉取develop分支的代码为例， 要拉取其余分支代码类似操作

新项目还在开发阶段，没有正式对外发布，所以开发同事合并代码到develop上(或者其他名称分支上)，而不是到master分支上

通过git拉取代码的时候，默认拉取的是master分支，如下图：
### 1.使用git命令拉取

命令：``git clone -b <branch name> <git url>``

``-b``参数创建分支名称的同时将此名称下的分支内容clone下来
