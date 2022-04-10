[TOC]
derivative calculator
## 无穷小，无穷大
无穷小指趋向0，无穷大指 $\infty$ 或 $-\infty$
> 等价无穷小

## 极限
---
**<font color = #FA58AC>数列极限</font>：若对于每一个正数$\varepsilon$，恒有序号N，使得n>N时，所有$x_n$的值均满足不等式<font color = green>$|x_n - a| < \varepsilon$</font> 。则称常数a是<font color = green>整序变量$x_n$</font>的极限**

**<font color = #FA58AC>函数极限</font>：对任意正数$\varepsilon$，存在数$M$使得，当 $ X>M $时 <font color = green>$|f(x) - A|< \varepsilon$</font>**

上面两个的区别：N只能是正整数，M为任意<br>
eg.  _n_ number
``` c++
typedef struct Node{
    void data;
    struct Node* next;
}Node;
/*
array means X_n
n type must be integer
*/
int main(){
    int array[n];
    memset(array,'\0',n);
    Node* node = (Node*)malloc(sizeof(Node));
    for (int i=0;i<array.length();i++){
        //addTailFunction() to call;
    }
}
```
### 极限存在准则
> **极限存在：<br>(1)对函数，函数单调有界是极限存在的充要条件<br>(2)对数列，数列收敛，则极限必定存在**

1. 夹逼定理
...

### 性质 
---
+ 若对于级数$\displaystyle\sum_{a=1}^n{x_a}$，有级数$\displaystyle\sum_{a=1}^n|{x_a}|$也收敛，则称为绝对收敛级数（可以改变求和顺序）
+

<font color = red>*两个重要极限*</font>

1. $$\lim_{x \to 0}\frac{sinx}{x} = 1$$
0. $$\lim_{x \to \infty}({1 + \frac{1}{x}})^x = e$$

<font color = red>*重要不等式*</font>

> $a^n > \frac{(a-1)^2}{4}n^2$ （当a>1时）

> $a^\frac{1}{n} - 1 < \frac{a-1}{n}$ （当a>1时）

指数函数时求极限，可以采用以$e$为底是个很好的选择。<br>如:$({1 + \frac{1}{x}})^x$ = $e^{xln(1+\frac{1}{x})}$

### 不定式
---

一共分为以下7种：

$\frac{0}{0},\frac{\infty}{\infty},\infty-\infty,0*\infty,1^\infty,0^\infty,0^0$ 

| 极限类型 | 常用方法 |
|:----:|:----|
| $\frac{0}{0}$ | 1.洛必达<br>2.等价无穷小<br>3.泰勒公式 |
### 极限求解
----

## 连续
定义: if $|x - a| < \delta $ then $|f(x) - f(a)| < \varepsilon$
> 注意：$函数极限不要求在f(x)在x_0处有定义,而连续需要$<br>
如果$$\lim_{x \to x_0 }f(x) = f(x_0)$$，则说明函数连续<br>数列$x_n$极限也不要求能通过公式取到，因为可能是无穷的


## 导数
---
> *可导必连续，连续不一定可导*

<font color = #FA58AC>几何意义：切线的斜率K（它是动态变化的,一个具体值）</font> 

$\Delta y$是精确值，$\ {dy}$是近似值，故有$\Delta y = \frac{dy}{dx}\Delta x$ <br>

### 极值
<font color = red>一阶导数为0，只是取极值的必要条件，而不是充要条件</font>

拐点：**二阶导数**为0的点，当 $\ddot{y}$ > 0时，图像为凹；< 0时图像为凸（即原函数下降的速度变缓，物理上可用加速度由正向0靠近，速度达到最大来理解）

### 复合函数求导法则
--：



## 微分
---
$\Delta y$ = $\Delta$ x $\cdot$ $\dot{y}$ + $\Delta x$ $\cdot$ $\alpha$ <br>
$\alpha$随$\Delta x$的变化而变化，高阶无穷小

## 积分
---
函数斜率值乘以$\Delta x$所形成的面积为原函数的值（或者说是原函数在区间内的高度之差）<br>

一般的，对于求积，有限级数比积分难算，所以转而求积分更好
