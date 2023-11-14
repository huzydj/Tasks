# git

## 使用前

要在git的文件目录下打开gitbash

## 基本命令

+ git  status 查看仓库状态 经常使用，便于查看和保持
+ git init 初始化git仓库
+ git add 加入文件
+ git commit 提交到git仓库 初次使用需要使用 git config --global user. name和email告诉git你是谁
+ git log 打开仓库提交日志，可以看到仓库的变更记录
+ git branch 可以查看分支情况，在后面加名称可以新建分支
+ git checkout 切换到某一个分支，如果加-名称可以创建并且切换到该分支
+ git merge 在某一目录下使用，将后面名称的分支合并到该目录下
+ git branch -d 删除某分支
+ git branch -D 强制删除
+ git tag 给当前目录加一个tag

## 绑定github

这里用shh通道和github通信

1. 使用shh-keygen -t rsa生成rsa算法的秘钥
2. 把id_rsa.pub复制到github-新的shh
3. 添加，使用shh -T git@github.com测试

	## 代码提交

push 和pull

git push ------ master （第一次要验证账户密码）

git pull ------ master 

git remote add ------ 链接 关联远程仓库

+ 下载

在某一个github项目里 clone or download 复制地址链接

在需要的目录下git clone 链接

