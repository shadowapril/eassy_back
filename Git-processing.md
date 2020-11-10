---
title: Git-processing
date: 2020-11-10 09:03:53
tags:
	- git
	- ssh-key
cover: https://w.wallhaven.cc/full/5w/wallhaven-5we787.jpg
---

###### git常用操作[attention]

---

>**1. 生成ssh-key
>
>```sh
>ssh-keygen -t rsa -C "youremail@example.com"		//生成key
>
>cat ~/.ssh/id_rsa									
>//查看key并且复制添加到git：进入你的github账号，在settings下，SSH and GPG keys下new SSH key，然后将id_rsa.pub里的内容复制到Key中，完成后Add SSH Key。
>
>ssh -T git@github.com 								//验证是否添加成功
>```

---

---

> **2. 