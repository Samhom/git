# git 查看分支
git branch -vv  --显示版本号、远程分支号、当前状态（是否merge到了master分支）
git branch      --只显示本地分支名称
git branch -a   --查看本地和远程仓库的所有分支
git branch -r   --单独直接查看远程仓库的所有分支

# 同步远程分支
git checkout -b --本地分支名x origin/远程分支名x

# 切换分支
git checkout 分支名

# 分支同步
git fetch       --将本地分支与远程保持同步
git fetch --all --将本地所有分支与远程保持同步
