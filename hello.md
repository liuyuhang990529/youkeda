绑定本地仓库到GitHub 

本地建立一个和空仓库同名的文件夹

git init 初始化 git仓库

若错误初始化某文件夹，只需要删除当前文件夹下面.git文件夹

使用git remote -v 查看当前git 仓库绑定的远程仓库,刚初始化的仓库是没有绑定远程仓库的，clone下的仓库是有远程绑定的。

若 git remote -v 是空白 是无绑定，才可以绑定，不然会提示冲突。

git remote add origin 仓库地址 用来绑定远程仓库。

git remote remove origin 移除绑定。。