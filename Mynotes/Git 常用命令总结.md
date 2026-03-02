git init           初始化仓库
git ls-files     查看暂存区的文件
git add (.   *.) 将工作区的文件送到暂存区
git status      git 仓库目前的状态
git clone       复制仓库
git  log          上传记录
git commit   将暂存区的文件送到本地仓库区
![[Pasted image 20260302094953.png]]
git ls-files 看暂存区的内容
git reflog  查看操作的命令
git diff  (+两个版本号||+HEAD)  查看
git rm +文件名  删除文件
echo 文件名 > .gitignore 将文件隐藏起来不会被提交（不能是版本库中的文件）
git clone    克隆仓库
git push remote branch 推送更新内容
git pull       拉取更新内容
