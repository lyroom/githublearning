## 初始化一个本地仓库
```bash
$ git init #初始化了一个本地仓库，建立了一个.git文件夹，被称为附属于该仓库的工作树
```
## 查看仓库状态
```bash
$ git status #记录着当前处于master还是branch分支，有无需要commit的文件等
##以下是状态
位于分支 master
要提交的变更：
  （使用 "git restore --staged <文件>..." 以取消暂存）
        修改：     "git\345\255\246\344\271\240.md"
```
## 上传文件到本地仓库
```bash
git add xxx.cpp #上传一个xxx.cpp文件
git add -A #上传当前文件夹下的所有文件
git add . #同上
```
## 提交到github仓库
```bash
$ git commit -m “本次提交的备注” #上传到master分支，并打上备注
$ gitgit commit #可以直接commit，之后再详细编辑备注
```
## 查看提交日志
```bash
$ git log
##以下是日志内容
commit b3f611dafea403f51c52a04491a23e1e4e059190 (HEAD -> master)
Author: lyroom <codingfish@outlook.com>
Date:   Sat Oct 12 13:07:04 2024 +0800

    这是我的第二次详细修改
    
    xxxxxxxxxxxxxxxxxxxxxxxxxxxx

commit d1f94f3bb752ad1fc2551cd9ccb06c8eee5a39c8
Author: lyroom <codingfish@outlook.com>
Date:   Sat Oct 12 13:04:45 2024 +0800

    第一次提交

##也可以简短一行的输出每次提交的修改
$ git log --pretty=short
##以下是日志内容
commit b3f611dafea403f51c52a04491a23e1e4e059190 (HEAD -> master)
Author: lyroom <codingfish@outlook.com>
Date:   Sat Oct 12 13:07:04 2024 +0800

    这是我的第二次详细修改

commit d1f94f3bb752ad1fc2551cd9ccb06c8eee5a39c8
Author: lyroom <codingfish@outlook.com>
Date:   Sat Oct 12 13:04:45 2024 +0800

    第一次提交
```

查看日志常用快捷键：和man操作，less操作基本一样
f：往后翻一页
b：往前翻一页