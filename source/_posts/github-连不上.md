---
title: github 连不上
date: 2023-07-23 21:55:50
updated: 2023-07-23 21:55:50
tags:
---



``` bash
    git config --global http.proxy http://127.0.0.1:1080
    git config --global https.proxy http://127.0.0.1:1080
``` 

``` bash
    git config --global --unset http.proxy
```

修改dns为114.114.114.114
[windows如何修改dns](https://zhuanlan.zhihu.com/p/265364903)

