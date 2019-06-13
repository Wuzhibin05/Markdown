# Gitbook上传到github

### 1，安装GIt工具

Git: <<https://git-scm.com/>>

### 2，配置邮箱和用户名

```shell
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```


### 3，初始化Git环境

 1.进入本地的项目目录，右键“Git Bash here”,调出git命令行界面，然后输入

```shell
git init 
```

 2.将目录下的所有文件上传，也可以将“.”换成具体的文件名

```shell
git add .
```

 3.将项目提交到本地仓库

```shell
git commit -m "注释语句"  
```

### 4，在github上创建仓库。



### 5，代码提交到仓库

将本地的代码关联到github上

```shell
git remote add origin 项目的github地址
```

 上传代码到github之前需要先pull  

```shell
git pull origin master 
```

上传代码到远程git仓库

```shell
git push -u origin master
```

本次培训的文档：<https://github.com/Wuzhibin05/Markdown>