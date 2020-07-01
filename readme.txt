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