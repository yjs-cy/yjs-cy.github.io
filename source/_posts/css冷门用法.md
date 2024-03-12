---
title: css冷门用法
date: 2024-03-11 14:39:18
description: 这个是我记录的一些css冷门用法，反正我很少用，不断更新中ing...
tags:
---
# 1.宽高比
**aspect-ratio: 1 / 1;** 指定盒子的宽高比为 1:1，即宽度和高度相等
```
img{
    width: 80%; /* 设置盒子的宽度 */
    aspect-ratio: 1 / 1; /* 指定盒子的宽高比为 1:1，即宽度和高度相等 */
    background-color: aqua;
    border-radius: 50%;
    transition: transform 0.5s;
} 
```
# 2.高度自适应
**height: fit-content;** 这将使容器的高度根据其内容自动调整。
```
#article {
    flex: 1;
    padding: 30px;
    height: fit-content;
}
```