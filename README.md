# examonline

#### 介绍
毕业设计


### git提交代码

## 前提

1.已经下载过Git Bash

（如果还没有下载过,请移步至其他博主的博客下载安装Git Bash后再回来继续）

2.有一个Git账号（耍个机灵hhh）

## 步骤
下面以上传项目course-system-fe为例

1.在Gitee上创建该项目的远程仓库

2.进入本地你想要上传的文件目录下，右键单击空白处，点击Git Bash Here

3.配置你的用户名和邮箱

git config --global user.name "xxx"
git config --global user.email "xxx"

 (P.S.如果不放心可以输入以下命令检查自己的用户名和邮箱)

git config user.name
git config user.email

4.在项目内空白处右键Git Bash Here，命令行输入下列命令，初始化本地仓库

git init

5.添加项目目录下所有文件至本地仓库

git add .   （注意这里有个点）

6.使用如下命令加入注释提交（此步骤必不可少！）

git commit -m '本次提交的说明'（说明信息为必填项，最好是信息有意义，便于后期理解）

7.将本地仓库与远程仓库相连接

首先在远程仓库复制http链接

然后输入下列命令（xxx为刚才复制的链接）

git remote add origin xxx

8.强制将远程仓库文件更新至指定远程仓库中（如果仓库为空可以跳过这一步骤）

git pull --rebase origin master

9.将本地仓库中的文件推送至指定的远程仓库中

git push -u origin master

10.最后回到Gitee网页，刷新一下即可！

到这里就大功告成了！