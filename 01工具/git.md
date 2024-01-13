Git 是一个强大的版本控制系统，提供了许多命令来管理代码库。

以下是一些常用的 Git 命令：

配置 Git 用户信息：

git config --global user.name "Your Name": 设置全局用户名。
git config --global user.email "your.email@example.com": 设置全局用户邮箱。
初始化仓库：

git init: 在当前目录下初始化一个新的 Git 仓库。
克隆仓库：

git clone <仓库URL>: 克隆远程仓库到本地。
基本提交操作：

git add <文件或目录>: 将文件或目录添加到暂存区。
git commit -m "Commit message": 将暂存区的更改提交到本地仓库。
查看状态和历史：

git status: 查看工作区和暂存区的状态。
git log: 查看提交历史。
分支操作：

git branch: 列出本地分支。
git branch <branch-name>: 创建新的分支。
git checkout <branch-name>: 切换到指定分支。
git merge <branch-name>: 将指定分支合并到当前分支。
远程仓库：

git remote: 列出远程仓库。
git remote add <remote-name> <remote-url>: 添加远程仓库。
git push <remote-name> <branch-name>: 推送本地分支到远程仓库。
git pull <remote-name> <branch-name>: 从远程仓库拉取更新。
解决冲突：

在合并分支或拉取更新时，如果有冲突，使用 git mergetool 或手动编辑文件来解决冲突。
撤销更改：

git reset <file>: 将文件从暂存区移除，但保留在工作区。
git reset --hard: 丢弃所有本地的修改，回到最近的提交状态。
查看和比较更改：

git diff: 查看工作区和暂存区的差异。
git diff <commit1> <commit2>: 查看两个提交之间的差异。
这只是 Git 命令的一小部分，Git 提供了许多其他命令和选项，具体用法可以通过 git --help 或查阅 Git 文档来获取。


## Git安装与下载
## 基础指令
* git init 初始化仓库
* git status 查看状态
* git add xxx 添加文件
* git commit -m "注释内容" 提交到本地仓库
* git log 查看提交日志
* git reset --hard commitID 版本回退 
## 分支
## 远程仓库
## IDE中使用Git



## 常用命令
### git命令

* git add
* git status
* git log
* git reset --hard ID
* git reflog
* git branch
* git git branch xxx
* git checkout xxx
* git checkout -b xxx
* git merge xxx
* git branch -d xxx
* master(main) develop feature hotfix test
* git fetch
* git pull
* git push

