---
title: xcrun error invalid active developer path
key: xcrun
tags: MaxOS errorFix
---

```shell
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools),
missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun
```

<!--more-->
解决方法，重装xcode command line：
```shell
xcode-select --install
```
如果没有解决问题，执行以下命令：
```shell
sudo xcodej-select -switch /
```

https://www.jianshu.com/p/50b6771eb853