# Git
## 1.简介
## 2.CentOS安装及配置
### 2.1.yum安装
```bash
[root@localhost ~]# yum -y install git
```
### 2.2.配置
### 2.2.1.配置Git的配置文件，username和email
```bash
[root@localhost ~]# git config --global user.name "your name"      //配置用户名
[root@localhost ~]# git config --global user.email "your email"    //配置email
```
可以查看配置
```bash
[root@localhost ~]# git config --global user.name      //查看用户名配置
[root@localhost ~]# git config --global user.email     //查看email配置
```
### 2.2.2.配置默认的文本编辑器 vim（因为git默认使用emacs作为编辑器）
```bash
[root@localhost ~]# git config --global core.editor vim
```
可以查看配置
```bash
[root@localhost ~]# git config --global core.editor
```
### 2.2.3.查看git的所有配置
```bash
[root@localhost ~]# git config --list
user.name=yanshiming
user.email=1447273249@qq.com
core.editor=vim
```
### 2.2.4.配置ssh
```bash
[root@localhost ~]# ssh-keygen -t rsa -C "your email"
```
提示输入路径，短语口令等，直接回车即可。完成后，用户家目录下的`.ssh`下会生成秘钥文件
```bash
[root@localhost ~]# ls ~/.ssh/
authorized_keys  id_rsa  id_rsa.pub  known_hosts
```
## 2.3.基本操作
### 2.3.1.新建git仓库并初始化
```bash
[root@localhost ~]# mkdir -p /home/git/repositories/test.git
[root@localhost ~]# cd /home/git/repositories/test.git
[root@localhost test.git]# git --bare init（初始化一个裸版本库）
Initialized empty Git repository in /home/git/repositories/test.git/
[root@localhost test.git]# touch README.md  
[root@localhost test.git]# git init
[root@localhost test.git]# git add readme
[root@localhost test.git]# git commit -m 'initial commit' readme
```
### 2.3.2.上传文件
进入你要下载文件的目录,然后初始化(已有仓库的情况下执行)
```bash
[root@localhost ~]# cd /home/git/repositories/work.git
[root@localhost work.git]# git init
```
创建一个本地仓库
```bash
[root@localhost work.git]# git remote add origin git服务器地址:YourName/XXX.git  //YourName为你登录git服务器的名称，XXX为仓库名称
```
选择上传的文件
```bash
[root@localhost ~]# git add "我要上传的文件或目录"
如果要上传所有文件，可以使用通配符`.`
[root@localhost ~]# git add .
```
提交
```bash
[root@localhost ~]# git commit -m "提交信息"
```
上传
```bash
[root@localhost ~]# git push origin master     //master为你要上传的分支
```
### 2.3.3.克隆仓库到本地
登录Git服务器，点击进入要克隆的仓库，选择`克隆或下载（Clone or download）`，会有两个地址http和ssh。根据个人情况复制其中一个地址，如果配置了ssh可以使用ssh，没有配置ssh可以使用http。
然后执行以下命令：
```bash
[root@localhost work.git]# git clone 刚才复制的地址
```
### 2.3.4.下载文件
拉取更新
```bash
[root@localhost work.git]# git fetch origin
```
将更新内容合并到本地分支
```bash
[root@localhost work.git]# git merge origin/master     //master为要拉取更新的分支
```
也可以使用`git pull`命令自动拉取更新并合并到本地分支
```bash
[root@localhost work.git]# git pull origin master    //master为要拉取更新的分支
```
