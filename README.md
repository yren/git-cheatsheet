# git 常用命令

[参考](https://pure-admin.cn/pages/git/#%E7%A8%8B%E5%BA%8F%E5%91%98%E5%BF%85%E5%A4%87%E6%8A%80%E8%83%BD%E4%B9%8B-git)

* git clone

```shell
# git clone
git clone xxx.git
```

* git branch

```shell
# 查看本地的 branch
git branch

# 查看远程的 branch
git branch -r

# 查看所有的 branch
# 远程分支用 remotes/* 前缀
git branch -a
* main
remotes/origin/main

# 创建 branch dev, 并切换
git checkout -b dev
git switch -c dev

# 切换到 dev branch
git checkout dev
git switch dev

# 删除分支 dev
git branch -d dev
# 强制删除（本地有未合并的变更）
git branch -D dev

# 查看当前 branch 详细信息(和远端关联)
git branch -vv
```

## github 初始化项目

```shell
echo "# git-cheatsheet" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:yren/git-cheatsheet.git
git push -u origin main
```
