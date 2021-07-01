---
layout: post
title:  核信息获取处理 Chapter 1~2
author: Repo Xu
date:   2021-07-01 11:01:00 +0800
categories: [Courses, 核信息获取与处理]
tag: [Course Review]
math: true
mermaid: true
pin: true
---

【别找了，没有第一章的提纲 ~】

*Table of Contents*

[toc]

# 2.1 名词解释

## 2.1.1 原子的能级

1. 原子核外电子按一定轨道绕核运动时，相应的原子处于一定的能量状态；
2. 一种原子绕行电子数目和运动轨道是一定的，因此，一种原子总是处于一系列确定的稳定能量状态。这一系列确定的稳定能量状态成为**原子的能级**，记为 $ W_i $；
3. 原子的能级是量子化的，即不连续的；
4. 当原子有较高能级跃迁到较低能级时，原子将以光的形式释放能量：

$$ h\nu = W_1 - W_2 \tag{1} $$

5. 将某种原子发射的各种频率的光子按波长排列，就构成该原子的发射光谱，也即**原子的光谱**。

## 2.1.2 原子核的能级

1. **中子和质子在原子核内不断运动**，运动状态不同，相应的能量状态不同。原子核的不同能量状态组成原子核的能级；
2. 原子核的能级是**不连续的**，即量子化的；
3. 当原子核获得的能量准确等于两个能级的能量差时，将由**低能级跃迁到高能级**，处于激发态；
4. 处于**激发态**的**原子核**是**不稳定**的，会自动从**激发态跃迁到较低能态**，同时以**电磁辐射**的形式释放出等于两个能级差的能量。

## 2.1.3 核辐射

​	不稳定的原子核衰变时发射出的，载能的，亚原子粒子。有的带电，有的不带电。

​	包括 $ \alpha $ 粒子、$ \beta $ 粒子、$ \gamma $ 粒子、中子、质子、裂变碎片等。

## 2.1.4 放射性活度

​	一定量的放射性核素在一定时间内发生的自发核衰变的次数与时间的比值，即 ：

$$ A = \frac{\Delta N_0} {\Delta t} \tag{2} $$

​	简化：亦称“衰变率”，指样品在单位是假内衰变掉的原子数。

## 2.1.5 衰变常数

​	表示一个原子核在单位时间内发生衰变的几率，即

$$ \lambda = \frac{-dN/dt} {N(t)} \tag{3} $$

$$ T_\frac{1} {2} = \frac{\ln2} {\lambda} = \frac{0.693} {\lambda} \tag{4}$$

# 2.2 填空题

## 2.2.1 

1. **Description**

   重核的衰变过程中，$ \alpha $ 粒子会获得大部分衰变能。

2. **Reason**

   衰变能并不会以热能的形式直接释放，而是转变为子核的动能。

## 2.2.2

1. **Description**

   在 U 系衰变中，由 U-238 衰变到 Pb-206，其中经历了 8 次 $ \alpha $ 衰变与 6 次 $ \beta $ 衰变。

2. **Reason**

$$ \begin{cases}\Delta A = 238 - 206 = 32 \\ \Delta Z = 92 - 82 = 10\end{cases} \tag{5} $$

$ \quad \quad If\ we\ assume\ that\quad x = \alpha;\ y = \beta^-,\ then $

$$ \begin{cases} 4x = 32 \\ 2x-y=10 \end{cases} \Rightarrow \begin{cases} x = 8 \\ y = 6 \end{cases} \tag{6} $$

$ \quad \quad Q.E.D. $

## 2.2.3

1. **Description**

   在 Th 系衰变中，由 Th-232 衰变到 Pb-208，其中经历了 6 次 $ \alpha $ 衰变与 4 次 $ \beta $ 衰变。

2. **Reason**

$$ \begin{cases}\Delta A = 232 - 208 = 24 \\ \Delta Z = 90 - 82 = 8\end{cases} \tag{7} $$

$ \quad \quad If\ we\ assume\ that\quad x = \alpha;\ y = \beta^-,\ then $

$$ \begin{cases} 4x = 24 \\ 2x-y=8 \end{cases} \Rightarrow \begin{cases} x = 6 \\ y = 4 \end{cases} \tag{8} $$

$ \quad \quad Q.E.D. $

