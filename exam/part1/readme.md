# Collatz Conjecture (考拉兹猜想)

## 问题描述
考拉兹猜想，也称为3n+1猜想，是一个未解决的数学问题。对于任何正整数n，按照以下规则反复操作，最终数值将收敛至1：
- 如果n是偶数，则将其除以2。
- 如果n是奇数，则将其乘以3并加1。

## 解答思路
本Notebook提供了一个Python函数用于生成给定正整数的考拉兹序列，并绘制了从3到30（间隔为3）的每个起始数字的考拉兹序列的收敛图。

## 如何使用代码
1. 运行上述Python单元格以定义`collatz_sequence`函数。
2. 调用该函数并传入任意正整数作为参数，以生成对应的考拉兹序列。
3. 代码输出将显示指定数字的考拉兹序列。
4. 可以修改循环中的范围或直接调用函数以输出不同数字的序列。

## 运行结果
![](![](2023-11-15-14-39-48.png).png)