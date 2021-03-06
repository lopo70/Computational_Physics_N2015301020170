# Exercise 12
## 问题
![](https://github.com/lopo70/Computational_Physics_N2015301020170/blob/master/Exercise%2012/%E6%8D%95%E8%8E%B7.PNG)
## 解题思路
波的传播有如下波动方程

<div align=center>
<a href="http://www.codecogs.com/eqnedit.php?latex=\frac{\partial&space;^{2}y}{\partial&space;t^{2}}=c\frac{\partial&space;^{2}y}{\partial&space;x^{2}}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\frac{\partial&space;^{2}y}{\partial&space;t^{2}}=c\frac{\partial&space;^{2}y}{\partial&space;x^{2}}" title="\frac{\partial ^{2}y}{\partial t^{2}}=c\frac{\partial ^{2}y}{\partial x^{2}}" /></a>
  
<div align=left>
我们假设有如下扰动
<div align=center>
<a href="http://www.codecogs.com/eqnedit.php?latex=y_{0}(x)=exp[-k(x-x_{0})^{2}]" target="_blank"><img src="http://latex.codecogs.com/gif.latex?y_{0}(x)=exp[-k(x-x_{0})^{2}]" title="y_{0}(x)=exp[-k(x-x_{0})^{2}]" /></a>
<div align=left>
在弦上施加两个如上的扰动，并使用程序模拟他们的传播，并通过选取任意的扰动起始点以及任意的扰动波振幅，来证明波的传播是独立的。
设定disturbance1的振幅为1

<div align=left>  

## 结果
### position of disturbance1 = 0， position of disturbance2 = 1，amp2 = 0.9
<div align=center>

![](https://github.com/lopo70/Computational_Physics_N2015301020170/blob/master/Exercise%2012/1.gif)
<div align=left> 

### position of disturbance1 = 0.1， position of disturbance2 = 0.9，amp2 = 0.3
<div align=center>

![](https://github.com/lopo70/Computational_Physics_N2015301020170/blob/master/Exercise%2012/2.gif)
<div align=left> 

### position of disturbance1 = 0.3， position of disturbance2 = 0.6，amp2 = 1.2
<div align=center>

![](https://github.com/lopo70/Computational_Physics_N2015301020170/blob/master/Exercise%2012/3.gif)
<div align=left> 

## 结论
任意两个波的传播互相独立，不会影响彼此之间的传播。
![源代码](https://raw.githubusercontent.com/lopo70/Computational_Physics_N2015301020170/master/Exercise%2012/1.py)

