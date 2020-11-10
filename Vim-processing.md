---
title: Vim-processing
date: 2020-11-10 08:42:21
tags:
	- vim
	- Ubuntu
cover: https://w.wallhaven.cc/full/2e/wallhaven-2eroxm.jpg
---

###### vim常用指令合集

---



> **1. 当前窗口打开多个文件：
>
> ```sh
> :sp file //水平分割打开第N个文件
> ```
>
> ```sh
> :vsp file //垂直分割打开第N个文件
> ```
>
> `使用ctrl + ww可以在各个文件之间切换`



---



> **2. 多行注释：
>
> ```sh
> 1-: ctrl + v 进入VISUAL BLOCK模式，选择要注释的区域
> 2-: 输入注释符，按Esc完成注释
> ```
>
> **3. 取消注释
>
> ```sh
> 1-: ctrl + v 进入VISUAL BLOCK模式，选择要注释的区域
> 2-: 使用d命令删除选中的区域，取消注释
> ```



---



