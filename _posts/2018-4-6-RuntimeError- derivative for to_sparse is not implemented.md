---
title: RuntimeError: derivative for [variable] is not implemented
key: RuntimeError
tags: pytorch errorFix
---

参考github issue：
···
https://github.com/foolyc/torchKNN/issues/1
···

在这个变量最后出现的地方使用···.detach()···方法
···
return inds.detach()
···
<!--more-->

hahaha
