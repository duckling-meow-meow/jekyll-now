---
layout: post
title: 能否成功
---

## 问题描述

定义一个函数，判断你的人生能否获得成功。

## 解题思路

成功需要野心，还需要努力，并且努力要配得上野心。

## c++代码

```
bool ifsucceed(int ambition,int pains){
  if(ambition<=0||pains<=0)
    return 0;
  else if(pains<ambition)
    return 0;
  else
    return 1;
}
```
