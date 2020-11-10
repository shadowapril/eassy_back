---
title: Python版本切换
date: 2020-11-09 13:21:37
tags:
	- python
	- Ubuntu PATH
cover: https://w.wallhaven.cc/full/rd/wallhaven-rd3pjw.jpg
---

##### 简介

```sh
今天在总结ctf解题过程时候发现python版本从2升级到3之后，volatility启动脚本失败了，因为python语法的改变。所以要从python3切换到python2，过程如下：

```
Step 1: 设置默认为python2

> `sudo update-alternatives --install /usr/bin/python python /usr/bin/python2 100`

Step 2: 设置默认为python3

> `sudo update-alternatives --install /usr/bin/python python /usr/bin/python3 150`

之后要设置默认版本可以用下面的命令：

> `sudo update-alternatives --config python`

##### 附加

`顺便提一下，Ubuntu的环境变量的设置，如果直接在/etc/profile中添加环境变量，会导致关闭终端之后在进入环境变量失效，因为普通用户默认的环境变量要使用~/.bashrc。所以把环境变量剪切到bashrc中更新即可`

> `source ~/.bashrc`