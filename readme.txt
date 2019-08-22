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
git reset --hard HEAD
git log 
git reflog        
git diff  HEAD -- readme.txt
 git checkout -- readme.txt
git reset HEAD readme.txt
ssh-keygen -t rsa -C 'yourEmail'
