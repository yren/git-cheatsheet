# git 常用命令

[参考](https://pure-admin.cn/pages/git/#%E7%A8%8B%E5%BA%8F%E5%91%98%E5%BF%85%E5%A4%87%E6%8A%80%E8%83%BD%E4%B9%8B-git)

```shell
# git clone
git clone xxx.git


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
