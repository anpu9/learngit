# 常见git操作

## 创建/删除远程库：

- `git remote add origin <u>ssh</u>'
- `git remote remove origin <u>ssh</u>'

## 分支操作

- 切换分支`git checkout <name>`
- 创建分支`git branch <name>`
- 创建并切换分支`git checkout -b <name>` **注意分支名字不必加双引号**
- 查看分支 `git branch`
- 合并分支`git merge <name>`是将指定分支合并到当前分支
- 删除分支`git branch -d <name>`