# idea-git




> #### 用户签名

```sh
#设置用户签名
git config --global user.name 用户名				
git config --global user.email 邮箱
```



> #### 本地库操作

```sh
#初始化本地库
git init

#查看本地库状态
git status

#添加到暂存区
git add 文件名
#将文件从暂存区删除
git rm --cached 文件名

#提交到本地库
git commit -m "日志信息" 文件名
```



> #### 版本控制

```sh
#查看版本日志  
git reflog
#查看详细版本日志
git log
#版本穿梭
git reset --hard 版本号
```



> #### 分支操作

```sh
#创建分支
git branch 分支名
#查看分支
git branch -v
#切换分支
git checkout 分支名
#合并分支
git merge 待合并分支名
```



> #### 分支冲突合并

1. 当分支合并发生冲突时, 需要手动修改文件, 需要删掉提示符并只保留一个改动
2. 在手动修改后, 需要重新添加到暂存区并提交本地, 当次提交不可携带文件名



> #### GitHub

```sh
#查看当前所有远程地址的别名
git remote -v
#添加别名
git remote add 别名 远程地址
#将本地库推送到远程库
git push 远程地址 分支名
#将远程库的代码拉取到本地
git pull 远程地址 分支名
#克隆远程库到本地
git clone 远程
```

