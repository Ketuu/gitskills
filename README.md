# gitskills

记录一些常用的git命令

## 常用git命令

>git config --global user.name "yourname"  
git config --global user.email "email"

### 操作之前执行以下命令行

>git init  
clear　　　　　(ctrl+l)  
git remote -v  
git pull  
git add -A 　　或者加文件全名  
git commit -m "message that you upload"  
ESC + wq退出编辑模式  
git push  　　　(git push -u origin master  第一次)  
git branch 　　(new branch name)  
git checkout branchname  　　切换分支  
git log　　　　英文状态下按Q退出  
git log --pretty=oneline 　　　只显示message  
前面那串黄色的就是提交的版本号
按下Esc (退出编辑状态)； 接着连按两次大写字母Z，保存好退出  
按下Esc键退出编辑模式，输入:wq 保存并关闭文件  
git reset --hard HEAD^  HEAD回退到上一个版本，文件变成上次提交修改前的状态  
git reset --hard 747f   　　后面加要回退的版本号  
git reflog  　　　　　　　查看历史记录的版本号id  
git reset HEAD \<file>　　撤销暂存区的修改（add）  
git diff \<filename> 　　　查看工作区和暂存区的不同  
rm xxx.xx   删除文件   git rm xx.xx  git commit  
git check out -- xxx.xx   把XX文件在工作区的修改全部撤销。  

### 关联远程服务器

>ssh-keygen -t rsa -C youremail@example.com  
生成ssh密钥  复制id_rsa.pub中的内容（user/.ssh/）

### 关联一个远程库

>$ git remote add origin git@github.com:Your name/aaa.git
