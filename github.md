# Git教程

## 拉取代码

git clone {url}

在要下载的文件夹空白处右键，然后点击git bash here，调出命令行。

表示从url中拉取代码到本地。

这个url是在gitlab中添加项目后，自动生成的sshtps，建议使用https。

## 创建一个新的分支

git branch {branch-name}

## 切换到新创建的分支

git checkout {branch-name}

## 在创建的分支上开发

## 查询当前分支的状态

git status

1. 需要你git add {file}
2. 需要git commit -am "这里面是要提交的注释"
3. nothing to commit , working tree clean，表示当前没任何文件添加、删除或修改

## 提交命令（本地）

git commit -am "这里面是要提交的注释"

这个命令会把当前的修改提交到当前所在的分支（test），但是Master分支是没有这个123.txt文件的。

## 查看提交的日志信息

git log

会显示出来当前分支提交的所有信息

## 提交到远端

git push origin {本地的分支}:{远端的分支}

## 从远端更新代码到本地

git pull origin {远端分支}

