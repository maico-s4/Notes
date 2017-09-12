# Git环境安装步骤

## 设置全局环境变量

```
huazy@macio-PC MINGW64 ~
$ git config --global user.name "macio-abap"

huazy@macio-PC MINGW64 ~
$ git config --global user.email ziyuhua@qq.com
```
### 确认设置结果
```
huazy@macio-PC MINGW64 ~
$ git config --list
core.symlinks=false
core.autocrlf=true
core.fscache=true
color.diff=auto
color.status=auto
color.branch=auto
color.interactive=true
help.format=html
rebase.autosquash=true
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
http.sslbackend=openssl
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.required=true
filter.lfs.process=git-lfs filter-process
credential.helper=manager
user.name=macio-abap
user.email=ziyuhua@qq.com
```
### 确认特定环境变量结果
```
huazy@macio-PC MINGW64 ~
$ git config user.name
macio-abap
```
# 配置Jekyll环境

## 设置安装目录
```
huazy@macio-PC MINGW64 ~
$ mkdir jekyll_demo
huazy@macio-PC MINGW64 ~
$ cd jekyll_demo
huazy@macio-PC MINGW64 ~/jekyll_demo
$ git init
Initialized empty Git repository in C:/Users/huazy/jekyll_demo/.git/
huazy@macio-PC MINGW64 ~/jekyll_demo (master)
$ git checkout --orphan gh-pages
Switched to a new branch 'gh-pages'

```
### 创建模板文件
```
huazy@macio-PC MINGW64 ~/jekyll_demo (gh-pages)
$ mkdir _layouts
huazy@macio-PC MINGW64 ~/jekyll_demo (gh-pages)
$ mkdir _posts

```