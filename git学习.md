## 初始化一个本地仓库
```bash
git init #初始化了一个本地仓库，建立了一个.git文件夹，被称为附属于该仓库的工作树
```
## 查看仓库状态
```bash
git status #记录着当前处于master还是branch分支，有无需要commit的文件等
```
## 上传文件到本地仓库
```bash
git add xxx.cpp #上传一个xxx.cpp文件
git add -A #上传当前文件夹下的所有文件
git add . #同上
```
## 提交到github仓库
```bash
git commit -m “本次提交的备注” #上传到master分支，并打上备注
```
## 查看提交日志
```bash
git log
```
