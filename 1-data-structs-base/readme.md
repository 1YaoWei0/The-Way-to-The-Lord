[TOC]

# 数据结构与算法

## 前言

> 程序 = 数据结构 + 算法

## 课程内容

1. 绪论；数据结构的基本概念
2. 基本数据结构
   1. 线性结构
   2. 非线性结构
3. 基本的数据处理技术

## 数据结构的研究内容

1. 具体问题抽象为数学模型
   1. 分析问题
   2. 提取**操作对象**
   3. 找出**操作对象**之间的关系
   4. 用数学语言描述
2. 设计算法

> 更多的，计算机被利用于**非数值计算**。例如数据库的数据管理。
>
> 数据结构是一门研究**非数值计算的程序设计**中计算机的**操作对象**以及它们之间的**关系**和**操作**的学科



## 基本概念和术语

1. 数据

   1. 数据元素和数据项 `数据的个体`
      1. 数据元素是数据的基本单位
      2. 数据项是数据元素的基本单位，且不再可分割
   2. 数据对象；性质相同的数据集合（**对象**含义的一个运用）`数据的子集`

2. 数据结构

## 抽象数据类型的表示和实现

![image-20241112194227881](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112194227881.png)

![image-20241112194453772](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112194453772.png)

![image-20241112194620173](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112194620173.png)

![image-20241112194655157](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112194655157.png)

## 算法与算法分析



![image-20241112195450897](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112195450897.png)

## 算法的定义

![image-20241112195533900](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112195533900.png)

## 算法与程序

![image-20241112195837771](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112195837771.png)

> 程序 = 数据结构 + 算法

## 算法与算法分析

> 算法特性：一个算法必须具备五大特性

![image-20241112200111644](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112200111644.png)

> 算法设计的要求

- 正确性

![image-20241112200153116](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112200153116.png)

- 可读性

![image-20241112200327862](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112200327862.png)

- 健壮性（Robustness）**鲁棒性**

![image-20241112200438511](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112200438511.png)

- 高效性

> 要求花费尽量少的时间和尽量低的存储需求

> 如何评价一个算法的好算法？

![image-20241112200802209](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112200802209.png)

> 时间效率与空间效率有时候是矛盾的

## 算法时间效率

![image-20241112200944526](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112200944526.png)

- 事后统计
- 事前分析

![image-20241112201137230](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112201137230.png)

> 算法运行时间 = 一个简单操作所需的时间 * 简单操作次数

![image-20241112201239752](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112201239752.png)

![image-20241112201426372](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112201426372.png)

> 所以最终 => **算法运行时间** = **每条语句频度**

**时间复杂度** = **算法的渐进时间复杂度**

## 基本语句

> n 问题规模，表示要处理的数据量

![image-20241112202724595](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112202724595.png)

![image-20241112202816831](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112202816831.png)

## 算法时间复杂度

![image-20241112203426824](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112203426824.png)

## 渐近空间复杂度

- 算法所需存储空间的度量
- 算法要占据的空间
  - 本身要占据的空间，输入/输出，指令，常数，变量等
  - 辅助空间

## 设计好算法的过程

抽象数据类型 = 数据的逻辑结构 + 抽象运算（运算的功能描述）

![image-20241112204204071](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241112204204071.png)



