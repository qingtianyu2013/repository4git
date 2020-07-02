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
git branch -d dev 删除dev分支
git log --graph命令可以看到分支合并图
git stash 可以把当前工作现场“储藏”起来，等以后恢复现场后继续工作
git stash list 暂存的存储列表
git stash apply 恢复暂存分支并不删除存储
git stash drop 删除暂存分支
git stash pop	恢复并删除=上两条
git cherry-pick 复制一个特定的提交到当前分支
git branch -D <name>  丢弃一个没有被合并过的分支
git remote  查看远程库的信息
git remote -v
git tag <tagname>用于新建一个标签
git tag 可以查看所有标签
git tag -d <tagname>可以删除一个本地标签
git push origin :refs/tags/<tagname>可以删除一个远程标签
git push origin <tagname>可以推送一个本地标签 master


