<!--
 * @Author: Connor2Chen 397080067@qq.com
 * @Date: 2024-09-05 17:47:47
 * @LastEditors: Connor2Chen 397080067@qq.com
 * @LastEditTime: 2024-09-05 18:06:53
 * @FilePath: \Learning-Note\02_HardWare\05_电路板部分\01_PCB_EMC.md
 * @Description: 
 * 
 * Copyright (c) 2024 by ${git_name_email}, All Rights Reserved. 
-->

---

[TOC]

---
---

# 一、布局


## 01.层数
### 关于VCC和GND的层数
#### VCC部分
```
假如一块板子只涉及单一电源，那么我们可以直接使用单一电源层；
```
```
假如一块板子涉及了多个电源，我们则需要视电源是否交错来选择层数，
若不交错，那么可以使用 电源层分割；
若交错，那么可以考虑使用多个电源平面；
```
#### GND部分
```
1.元件下面尽量有完整地平面；
2.那些高频、重要信号尽量也需要有相邻地平面（铺地孔）；
3.关键电源处，最好也需要有相邻地平面；
```
<br>

### 信号层数



## 02.电源层、底层、信号层的相对位置
### VCC、GND











---

