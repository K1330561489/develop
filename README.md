echo "# develop" >> README.md

初始化本地仓库命令
git init

添加文件到暂存区
git add README.md

将暂存区的文件提交到仓库，必须附带说明，比如："first commit"
git commit -m "first commit"

重命名当前分支
git branch -M main

添加远程链接
git remote add origin https://github.com/K1330561489/develop.git

将本地仓库main分支的内容推送到远程
git push -u origin main
