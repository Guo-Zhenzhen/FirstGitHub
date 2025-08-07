本地有项目代码，远程空仓库一个，如何把本地项目代码推送到远程仓库？



1. git init
2. git add .
3. git commit -m 'first commit'
4. git remote add origin https://github.com/Guo-Zhenzhen/FirstGitHub.git
5. git push -u origin main

修改已存在的origin地址：
git remote set-url origin https://github.com/Guo-Zhenzhen/FirstGitHub.git

先删除，在添加
git remote remove origin
git remote add origin https://github.com/Guo-Zhenzhen/FirstGitHub.git