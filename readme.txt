git init  初始化目录
git add readme.txt。添加命令
git commit -m "wrote a readme file"  提交命令
git status  查看状态
git diff readme.txt  查看修改的不同
git reset --hard HEAD^ 回退到上一个版本
git reflog用来记录你的每一次命令
git checkout -- file可以丢弃工作区的修改
git checkout -- file命令中的--很重要，没有--，就变成了“切换到另一个分支”的命令
git rm 删掉 文件，并且git commit
要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
关联后，使用命令git push -u origin master第一次推送master分支的所有内容
git clone https://github.com/qingtianyu2013/nick.git  克隆到本地
git checkout -b dev   加上-b参数表示创建并切换
git branch命令查看当前分支
git checkout dev 切换到dev分支
git merge dev 命令用于合并指定(dev)分支到当前分支
git branch -d dav 删除dev分支

