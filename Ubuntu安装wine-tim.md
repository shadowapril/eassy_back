---
title: Ubuntu安装wine-tim
date: 2020-11-19 22:39:42
tags:
	- Ubuntu
	- wine
	- tim
cover: https://w.wallhaven.cc/full/e7/wallhaven-e7zqro.jpg
---

#### Ubuntu安装TIM

> *1. 首先下载deepinwine的安装文件，地址如下：

```
https://gitee.com/wszqkzqk/deepin-wine-for-ubuntu.git
```

> *2. 接下来下载wine-tim[可能需要注册一个gitee账号登录才能下载]，地址如下：

```
https://gitee.com/login?redirect_to_url=http%3A%2F%2Fgitee.com%2Fwszqkzqk%2Fdeepin-wine-containers-for-ubuntu%2Fraw%2Fmaster%2Fdeepin.com.qq.office_2.0.0deepin4_i386.deb
```

> *3. 然后进入第一步下载的文件夹 deepin-wine-for-ubuntu，安装：

```
./install.sh
```

> *4. 安装TIM的deb包

```
sudo dpkg -i deepin.com.qq.office_2.0.0deepin4_i386.deb
```

以上就是Ubuntu18.04环境下Wine-TIM的安装过程:rocket:，如有错误欢迎指正