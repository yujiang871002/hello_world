# hello_world
一个学习、测试及使用git、github、markdown等工具的工程


## 使用终端命令行将本地项目上传到Github

第一步：建立本地Git仓库

切换到本地项目的根目录下, 执行git init命令, 使之成为一个git仓库。

第二步：将本地项目工作区的所有文件添加到暂存区

git add .

如果想添加项目中的指定文件，那就把.改为指定文件名即可

第三步：将暂存区的文件提交到本地仓库

git commit -m "first commit"

注意：冒号里面写注释语句

第四步：在Github上创建自己的repository

第五步：将本地仓库关联到Github上

git remote add origin https://github.com/yujiang871002/hello_world.git

第六步：最后一步，将代码由本地仓库上传到Github远程仓库

git push -u origin master

# 一些常用命令
撤销修改：git checkout -- file

删除文件：git rm file

查看状态：git status

添加记录：git add file 或 git add .

添加描述：git commit -m "miao shu nei rong"

同步数据：git pull

提交数据：git push origin name

查看分支：git branch

创建分支：git branch name

切换分支：git checkout name

创建+切换分支：git checkout -b name

合并某分支到当前分支：git merge name

删除分支：git branch -d name

删除远程分支：git push origin :name
