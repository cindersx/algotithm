# 远程库
- 查看自己的key
```linux
cat /Users/daixin/.ssh/id_rsa.pub
```
- 远程库关联
```linux
git remote add origin https://github.com/*/PROJ_NAME.git
```
- 克隆项目到本地
```linux
git clone
```

# 提交代码
```linux
//文件添加到仓库（.代表提交所有文件）
git add .
//把文件提交到本地库
git commit -m "提交注释"
//推送到远程库
git push origin <branch name>
//查看当前分支状态
git status
```

# 分支branch
- 查看分支
```linux
git branch -a 
```
- 创建分支
```linux
git branch <branch name>
```
- 切换分支
```linux
git checkout <branch name>
```
- 创建+切换分支
```linux
git checkout -b <branch name>
```
- 合并某分支到当前分支
```linux
git merge <branch name>
```
- 删除分支
```linux
git branch -d <branch name>
```
- 删除远程分支
```linux
git push origin :<branch name>
```

