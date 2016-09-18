# Lab 1

> 本节目标

> 1.理解数据类型

> 2.学习从控制台读取输入、显示输出

> 3.理解基础运算符

## 提交作业

**提交**：将代码压缩，命名为 `学号_姓名` 例如 `13302010032_zhouyi`，提交至 `FTP` 站点（`ftp://10.132.141.33`）的 `work_upload` 文件夹下。

## `++i` VS `i++`

*此题不需提交*

下面代码的运行结果是什么？先根据学过的知识计算，再通过编写代码求解。

```java
int x = 1;
int ans1 = x++;
int ans2 = ++x;
int ans3 += (x++) + (++x); // 尽量避免这种代码写法
int ans4 += (x++) + (++x); // 尽量避免这种代码写法
```

## 计算三角形面积

**要求**

从控制台依次输入三个点的横坐标和纵坐标 `x1 y1 x2 y2 x3 y3` ，求其构成的三角形面积，并打印出来。

**提示**

1.**不必考虑** 三点共线的情况

2.三角形面积的计算可以通过 [必应搜索引擎 www.bing.com](http://www.bing.com) 搜索关键词 **海伦公式** 

3.使用 `Scanner` 从控制台读取输入

**输入样例** 

`0 0 1 0 0 1`

**输出样例** 

`0.5`

**输入样例**

`3 0 0 0 0 4`

**输出样例**

`6`
