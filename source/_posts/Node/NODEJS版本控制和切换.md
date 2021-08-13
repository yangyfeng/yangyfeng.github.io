---
type: blog
title: nodejs版本控制和切换
categories:
  - 后端
tags:
  - Node
abbrlink: 873788fc
date: 2021-08-13 00:00:00
---

nvm是node.js的版本管理器，可以安装和切换不同版本node.js

### 第一步：下载

下载地址：https://github.com/coreybutler/nvm-windows/releases

### 第二步：安装

按照提示完成安装即可，安装完成后可以检测一下是否安装成功

在cmd命令行输入nvm,如果出现nvm版本号和一系列帮助指令，则说明nvm安装成功。

### 第三步：修改settings.txt

在你安装的目录下找到settings.txt文件，打开后加上 

```
node_mirror: https://npm.taobao.org/mirrors/node/ 
npm_mirror: https://npm.taobao.org/mirrors/npm/
```

这一步主要是将npm镜像改为淘宝的镜像，可以提高下载速度。

### 第四步：node.js 安装

可以先使用 num list 查看本地已安装的版本

然后使用 nvm list available 查看所有版本

nvm常用命令

```bash
nvm list 查看已经安装的版本
nvm list installed 查看已经安装的版本
nvm list available 查看网络可以安装的版本
nvm version 查看当前的版本
nvm install 安装最新版本nvm
nvm use <version> ## 切换使用指定的版本node
nvm ls 列出所有版本
nvm current显示当前版本
nvm alias <name> <version> ## 给不同的版本号添加别名
nvm unalias <name> ## 删除已定义的别名
nvm reinstall-packages <version> ## 在当前版本node环境下，重新全局安装指定版本号的npm包
nvm on 打开nodejs控制
nvm off 关闭nodejs控制
nvm proxy 查看设置与代理
nvm node_mirror [url] 设置或者查看setting.txt中的node_mirror，如果不设置的默认是 https://nodejs.org/dist/
nvm npm_mirror [url] 设置或者查看setting.txt中的npm_mirror,如果不设置的话默认的是： https://github.com/npm/npm/archive/.
nvm uninstall <version> 卸载制定的版本
nvm use [version] [arch] 切换制定的node版本和位数
nvm root [path] 设置和查看root路径
```