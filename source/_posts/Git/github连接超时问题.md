---
type: blog
title: github连接超时问题
tags:
  - Git
categories:
  - 开发工具
abbrlink: d8976663
date: 2021-04-21 00:00:00
---

## Github出现连接超时

**解决办法**

1、打开本机dns配置文件

文件路径在`C:\Windows\System32\drivers\etc`

2、获取要访问的相关网站的IP

访问[查询IP](https://www.ipaddress.com/)

搜索框内分别输入`github.com`和`github.global.ssl.fastly.net`查询对应的IP地址，然后如上图所示格式添加上配置就可以了

[![cbYzMF.png](https://z3.ax1x.com/2021/04/21/cbYzMF.png)](https://imgtu.com/i/cbYzMF)

3、测试

powershell里`ping`一下

`ping github.com`