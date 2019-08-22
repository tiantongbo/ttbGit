git config --global user.name 'yourname'
git config --global user.email 'email'

mkdir dir  创建目录
cd 进入目录
pwd 显示当前目录
git init  初始化git版本仓库
git add   添加到工作区,暂存区
git commit -m   添加到本地仓库
git status   查看结果
git 分为工作区,暂存区,本地仓库,代码托管
HEAD^ 回退上一个版本HEAD^^回退上2个版本,HEAD~1002
git reset --hard HEAD 会退到一个版本
git log       查看日志
git reflog        查看日志 
git diff  HEAD -- readme.txt        查看与版本库的区别
 git checkout -- readme.txt         把工作区的内容撤销
git reset HEAD readme.txt           从暂存区修改   
 
ssh-keygen -t rsa -C 'yourEmail'      生成id_ssh  id_ssh_pub
git remote add origin                  关联远程库
git push -u origin master             像远程库推送

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>
dsadasdadqad    mastr