# git-practice
git 练习项目

#### git log
使用这个命令可以查看整个 commit 树结构。
```git
git log --oneline --abbrev-commit --graph
```
参数说明如下：
> -- oneline：显示一行，在一行里显示 SHA-1 hash 值、分支和HEAD指向哪个commit、commit提交说明。

> -- abbrev-commit：将SHA-1 hash值显示为一个短值，默认显示前 7 位（完整的有 40 位）,前 7 位就可以唯一定位到一个commit，不需要完整的 40 位。

> -- graph：图形化显示，显示为树形。


// add something for testß
