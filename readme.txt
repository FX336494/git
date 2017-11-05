git config --global user.email "2252599083@qq.com"
1、git init 
2、git add file
3、git commit -m 'adfas'
4、git checkout -- file
5、git reset HEAD file  //这个是提交到了缓存区  执行此命令会撤消 然后执行4命令撤消工作区


关联远程库
1、git remote add origin https://github.com/FX336494/gig.git
2、git push -u origin master 


//将本地文件推送到github 
git add file 
git commit -m '注释'
git push -u origin master


分支
1、创建并切换分支
	git checkout -b name
2、删除分支  git branch -d name

Git鼓励大量使用分支：

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>

create a new branch f1
createings
create a branch of dev
我是f2分支，我做了些功能。

我是dev分支