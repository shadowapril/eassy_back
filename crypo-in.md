---
title: crypo in
date: 2020-10-30 09:41:55
tags:
	- ctf
	- crypto
	- base64
	- python
cover: https://w.wallhaven.cc/full/96/wallhaven-963yqw.png
---

> 四月在写作课上打开了CTF-wiki，开始了密码学的入坑之路……

#### 单刀直入

``` sh
#题目已更新 2020-1-11 11:09# 一种很著名的编码，你会吗？ 请将以下“密码”解码后，得到flag。 
N0NDRTc5OEUtNjkyMC00NjI2LUE4RDctMzUyQUUyQUMyODk5
```

题目解析：

已经告诉我们直接解密就行了，所以还是很友好的，那就解密看看。此处密文格式很像base64，因此优先测试base64解密。

> ```python
> import base64
> encoded="N0NDRTc5OEUtNjkyMC00NjI2LUE4RDctMzUyQUUyQUMyODk5"
> base64.b64decode(encoded)
> ```
>
> 然后你so easy的找到了flag:
>
> ```
> 7CCE798E-6920-4626-A8D7-352AE2AC2899
> ```

That's all.

