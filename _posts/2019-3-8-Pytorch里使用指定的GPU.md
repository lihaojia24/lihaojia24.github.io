---
title: Pytorch里使用指定的GPU
key: Pytorch
tags: Pytorch command
---

## 终端中
···
CUDA_VISIBLE_DEVICES=1 python my_script.py
···

<!--more-->

## 代码中
···
import os
os.environ["CUDA_VISIBLE_DEVICES"] = "1"
···
