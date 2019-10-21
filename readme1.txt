repository

创建版本库
mkdir v0.0.1
cd v0.0.1
pwd
git init

把文件添加到本地仓库
/**没有提示就是正常
git add readme.txt  

把文件提交到远程仓库
git commit -m '将本地文件添加到远程仓库'

查看当前本地库的状态
git status

查看文本变化
git diff <file>

查看已有版本
git log 
或 git log --pretty=oneline
或 

回退版本
/**回退上一个版本
git reset --hard HEAD^
/**回退上两个个版本
git reset --hard HEAD^^
/**回退指定版本号
git reset --hard 1094a

工作区 dir
版本库 .git
	暂存区
	master
	head
git add ->暂存区
git commit ->分支


撤销修改
git checkout -- [file]

删除文件
git rm readme.txt
git commit -m 'remove readme.txt'
