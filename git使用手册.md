# git使用手册

## git checkout

1. 用于工作分支的切换，当我们从git上clone一个项目后，只会默认创建一个master本地分支，其他的都是远程分支，如果我们想写环岛远程分支的话：

   `git branch -a`		查看所有的分支

   `git checkout branchName`	切换到远程分支

2. 新建分支的同时切换到该分支

   `git checkout -b newBranch`

