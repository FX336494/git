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