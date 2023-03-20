# ML_notes

> 参照2014版吴恩达机器学习课程笔记

## 1.概述

没有确定的定义。从经验中学习，解决任务，达到性能度量值。

无监督学习，自动聚类个体到各个分类。聚类学习只是无监督学习中的一种。

### 1.1 梯度下降

开始随机选择一个参数的组合计算代价函数，然后寻找下一个能让代价函数下降最多的参数组合，持续这么做，直到到达一个局部最小值。接着选择不同的参数组合，得到不同的局部最小值。

### 1.2 矩阵求导

$$
\frac{d AB}{dB}=A^T\\
\frac{dX^TAX}{dX}=2AX
$$

### 1.3 回归公式推导

代价函数：
$$
J(\theta)=\frac{1}{2m} \sum_{i=1}^{m}(h_{\theta}(x^{i})-y^{(i)})^2
$$
其中：$h_{\theta}(x)=\theta_0x_0+\theta_1x_1+\theta_2x_2+\cdots+\theta_nx_n=\theta^TX$
$$
\frac{\partial J(\theta)}{\partial \theta}=X^TX \theta-X^Ty=0\\
\theta = (X^TX)^{-1}X^Ty
$$

## 2.逻辑回归

Logistic Regression，实际上是一个分类算法。输出变量在 0-1 之间。

























