---
layout: post
title: 线性空间(一)
date: 2021-01-18 15:00
category: Math
author: Bao
tags: [Math]
summary: 映射,线性空间与n维向量空间的定义
---

若对应法则f满足

 $$
 A\rightarrow B,其中每个a\in A对应唯一的b\in B
 $$

则称f是A到B的一个**映射**,b是a在f下的**像**,记作f(a).称a是b在f下的*一个***原像**.

A称为**定义域(Domain)**,B称为**陪域**(Codomain).$f(A):= \{f(a)|a\in A\}$称为**值域**.

若f(A) = B,则f称为一个**满射**.
如果A中不同元素在f下的像不同,称f为**单射**.
如果f既是单射又是满射,则f称为一个**双射**(一一对应).

---


**定义** 笛卡尔积
$$
 S \times M :=\{(a,b)|a \in S,b \in M\} 
$$

称为S与M的**笛卡尔积**.

---

**定义1**

非空集合S上的一个**代数运算**是指$S\times S$到S的一个映射.

> 注意极限不是代数运算

---

**定义2**

设V是一个非空集合,K是一个数域.

如果V上有一个运算,称为加法,即

$$(\alpha ,\beta ) \rightarrowtail \alpha+\beta$$

K和V之间有一个运算,称为**数量乘法**.即 
$$
K \times V \rightarrow V:(k,\alpha) \rightarrowtail k\alpha
$$

且满足8条运算性质(不再赘述)

V就称为数域K上的一个**线性空间**.

---
令
$$
 K ^{n} = \{(a_1,a_2,...a_n)|a_i \in K,i = 1,2,...,n \} 
$$

 规定
 $$
  (a_1,a_2,...a_n)=(b _1,b _2,...,b _n)\\
  \stackrel{\triangle}{\iff} \\
  a_i = b_i,i=1,2,...,n.
 $$

 规定

$$
\begin{aligned}
    数量乘法\ &k(a_1,a_2,,...,a_n)=(k a_1,k a_2 ,...,k a_n)\\
 加法\ &(a_1,a_2,...a_n)+(b _1,b _2,...,b _n)=(a_1+b _1,a_2+b _2,...,a_n+b _n)
\end{aligned}
$$ 

并满足8条运算性质

|加法|数乘
|---|---
|交换律|单位元素
|结合律|交换律
|零元素|左分配律
|负元素|右分配率

则 $K^n是一个K上的n维向量空间.$

