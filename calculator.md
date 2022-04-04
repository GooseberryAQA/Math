[TOC]
derivative calculator
## 无穷小，无穷大
无穷小指趋向0，无穷大指 $\infty$ 或 $-\infty$
> 等价无穷小
---

## 极限定义
**数列极限：若对于每一个正数$\varepsilon$，恒有序号N，使得n>N时，所有$x_n$的值均满足不等式<font color = green>$|x_n - a| < \varepsilon$</font> 。则称常数a是整序变量$x_n$的极限**
**函数极限**

> ***极限存在：函数单调有界是极限存在的充要条件***
---

### 性质
+ 若对于级数$\displaystyle\sum_{a=1}^n{x_a}$，有级数$\displaystyle\sum_{a=1}^n|{x_a}|$也收敛，则称为绝对收敛级数（可以改变求和顺序）
+

<font color = red>两个重要极限</font>

1. $$\lim_{x \to 0}\frac{sinx}{x} = 1$$
0. $$\lim_{x \to \infty}({1 + \frac{1}{x}})^x = e$$

<font color = red>重要不等式</font>

> $a^n > \frac{(a-1)^2}{4}n^2$ （当a>1时）


指数函数时求极限，可以采用以$e$为底是个很好的选择。<br>如:$({1 + \frac{1}{x}})^x$ = $e^{xln(1+\frac{1}{x})}$
## 导数
<font color = #FA58AC>几何意义：切线的斜率K（它是动态变化的）</font> <br>

$\Delta y$是精确值，$\ {dy} $是近似值，故有$\Delta y = \frac{dy}{dx}\Delta x$ <br>

### 极值
<font color = red>一阶导数为0，只是取极值的必要条件，而不是充要条件</font>

拐点：**二阶导数**为0的点，当 $\ddot{y}$ > 0时，图像为凹；< 0时图像为凸（即原函数下降的速度变缓，物理上可用加速度由正向0靠近，速度达到最大来理解）

### 复合函数求导法则
--：

---

## 微分
$\Delta y$ = $\Delta$ x $\cdot$ $\dot{y}$ + $\Delta x$ $\cdot$ $\alpha$ <br>
$\alpha$随$\Delta x$的变化而变化，高阶无穷小

## 积分
函数斜率值乘以$\Delta x$所形成的面积为原函数的值（或者说是原函数在区间内的高度之差）<br>

一般的，对于求积，有限级数比积分难算，所以转而求积分更好
