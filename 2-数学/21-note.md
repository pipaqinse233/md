[toc]

> 本部分主要是对现行高中课本的补充，
> 大多是过于抽象的概念，看看就行了。

# 代数
## 函数

### 第一章  幂函数、指数函数和对数函数

#### 集合

##### 集合
**集合**（简称**集**）：一组对象的全体．
**元素**： 集合里的各个对象．
**有限集**：含有有限个元素的集合．
**无限集**：含有无限个元素的集合．
集合的性质:  
 * **确定性** 
 * **互异性**
 * **无序性**

集合的表示方法: 
 * **列举法**: 
    把元素中的元素一一列举出来，写在大括号内表示集合的方法．
 * **描述法**:
 把集合中的元素公共属性描述出来，写在大括号内表示集合的方法．
    集合同元素的关系: 
 * **属于**（**$\in$**）
 * **不属于**（**$\notin$**）

#### 二  映射与函数
#### 三  幂函数
#### 四  指数函数和对数函数
### 第二章  三角函数
#### 一  任意角的三角函数
##### 2.1  角的概念的推广
**角**: 由一条射线绕着它的端点旋转而成．
* **始边**: 旋转开始时的射线．
* **终边**: 旋转终止时的射线．
* **顶点**: 射线的端点．

角的分类：
 * **正角**: 按逆时针方向旋转所形成的角．
 * **负角**: 按顺时针方向旋转所形成的角．
 * **零角**: 未做任何旋转所形成的角．
 * **象限角**: 角的终边在第几象限，就说这个角是第几象限的角 (或说这个角属于第几象限) ．
 * **轴线角**: 角的终边在坐标轴上．

一般地，**所有与$\alpha$角终边相同的角，连同$\alpha$角在内 (而且只有这样的角) ，可以用式子
$2k\pi + \alpha, k \in \mathbb Z$
来表示．组成的集合可记作：
$ \{\beta | \beta = 2k\pi + \alpha, k \in \mathbb Z \} $**

##### 2.2  弧度制
**角度**：
*  周角的$\frac{1}{360}$为$1^{\circ}$的角．

**角度制**：
*  用角度做单位来度量角的制度．

**弧度**：
*  等于半径长的圆弧所对的圆心角为$1 \mathrm{rad}$的角．

**弧度制**:
*  用弧度做单位来度量角的制度．

一般地，**正角的弧度数为正数，负角的弧度数为负数，零角的弧度数为零，任一已知角$\alpha$的弧度数的绝对值$\left| \alpha \right|=  \frac{l}{r}$，其中$l$为以$\alpha$作为圆心角时所对圆弧的长$r$为圆的半径．**

**圆弧长公式**：$$l =\left| \alpha \right| r$$
**扇形面积公式**：$$S = {l \over R} \cdot {1 \over 2\pi} \cdot \pi R^2 = {1 \over 2}\left| \alpha \right| R^2 ={1 \over 2}lR$$
    
##### 2.3  任意角的三角函数
设$\alpha$是一个任意大小的角．角$\alpha$的终边上任意一点$P$的坐标是$(x,y)$，它与原点的距离是$r(r >0)$，那么角$\alpha$的**正弦**、**余弦**、**正切**、**余切**、**正割**、**余割**分别是

| 三角函数                | 定义 | 定义域$(k \in \mathbb Z)$ | Ⅰ | Ⅱ | Ⅲ | Ⅳ |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| 正弦函数$\sin(\alpha)$ | $\frac{y}{r}$ | $\alpha \in \mathbb R$ | + | + | - | - |
| 余弦函数$\cos(\alpha)$ | $\frac{x}{r}$ | $\alpha \in \mathbb R$ | + | - | - | + |
| 正切函数$\tan(\alpha)$ | $\frac{y}{x}$ | $\alpha \in \mathbb R$ 且 $\alpha \neq {\pi \over 2} + k\pi$ | + | - | + | - |
| 余切函数$\cot(\alpha)$ | $\frac{x}{y}$ | $\alpha \in \mathbb R$ 且 $\alpha \neq k\pi$ | + | - | + | - |
| 正割函数$\sec(\alpha)$ | $\frac{r}{x}$ | $\alpha \in \mathbb R$ 且 $\alpha \neq {\pi \over 2} + k\pi $ | + | - | - | + |
| 余割函数$\csc(\alpha)$ | $\frac{r}{y}$ | $\alpha \in \mathbb R$ 且 $\alpha \neq k\pi$ | + | + | - | - |

##### 2.4  同角三角函数的基本关系式
1. 倒数关系：
  * $\sin(\alpha)\csc(\alpha) = 1$
  * $\cos(\alpha)\sec(\alpha) = 1$
  * $\tan(\alpha)\cot(\alpha) = 1$

2. 商数关系：
  * $\tan(\alpha) = {\sin(\alpha) \over \cos(\alpha)}$
  * $\cot(\alpha) = {\cos(\alpha) \over \sin(\alpha)}$

3. 平方关系：
  * $\sin^2(\alpha) + \cos^2(\alpha) = 1$
  * $\tan^2(\alpha) + 1 = \sec^2(\alpha)$
  * $\cot^2(\alpha) + 1 = \csc^2(\alpha)$

上述各式均为**恒等式**．
##### 2.5  诱导公式
$\sec(\alpha)$与$\csc(\alpha)$并不常用，故下表省略．

|  | $-\alpha$ | $\pi - \alpha$ | $\pi + \alpha$ | $2\pi - \alpha$ | $2k\pi + \alpha$ |
  |:-:|:-:|:-:|:-:|:-:|:-:|
| $\sin$ | - | + | - | - | + |
| $\cos$ | + | - | - | + | + |
| $\tan$ | - | - | + | - | + |
| $\cot$ | - | - | + | - | + |

概括：**$-\alpha$，$\pi - \alpha$，$\pi + \alpha$，$2\pi - \alpha$，$2k\pi + \alpha$的三角函数值等于$\alpha$的同名函数值，前面加上一个把$\alpha$看成锐角时原函数值的符号．**


#### 二  三角函数的图像和性质
**性质**：
  | 函数名 | 奇偶性 | 周期性 | 有界性 | 一阶导数 | 二阶导数 |
  |:-:|:-:|:-:|:-:|:-:|:-:|
  | $\sin(x)$ | 奇 | $T = 2\pi$ | 1 | $\cos(x)$ | $-\sin(x)$ |  
  | $\cos(x)$ | 偶 | $T = 2\pi$ | 1 | $-\sin(x)$ | $-\cos(x)$ |
  | $\tan(x)$ | 奇 | $T = \pi$ | 无界 | ${\sin^2(x) + \cos^2(x)}\over \cos^2(x)$ | ${2\sin(x)\cos^2(x) + \sin^3(x)}\over \cos^3(x)$ |
  | $\cot(x)$ | 奇 | $T = \pi$ | 无界 | $-{1 \over \sin^2(x)}$ | ${2\sin^2(x)\cos(x)+2\cos^3(x)}\over \sin^3(x)$ |
  | $\sec(x)$ | 奇 | $T = 2\pi$ | 无界 | $\sin(x) \over \cos^2(x)$ | ${\cos^2(x) + 2\sin^2(x)}\over \cos^3(x)$ |
  | $\csc(x)$ | 偶 | $T = 2\pi$ | 无界 | $-{\cos(x) \over \sin^2(x)}$ | $-{{2\cos(x) + \sin^2(x)}\over \sin^3(x)}$ |

**图像**（一个最小正周期内）：由上表，可得
![](media/16495610024847.png)

##### 函数$y = A\sin(\omega x + \varphi), (A > 0, \omega > 0, 0 \leqslant \varphi < 2\pi), x \in \mathbb R$的图像

**作法**：
1. 作出$y = \sin(x)$
2. 向左平移$\varphi$个单位
3. 横坐标缩短到原来的$1 \over \omega$倍
4. 纵坐标伸长到原来的$A$倍

表示振动量时参数含义：
* **振幅**$A$
* **周期**$T = {2\pi \over \omega}$
* **频率**$f = {1 \over T} = {\omega \over 2\pi}$
* **相位**$\omega x + \varphi$
* **初相**$\varphi$

### 第三章 两角和与差的三角函数公式
#### 两角和与差
* $C_{\alpha \pm \beta}$：
$\cos(\alpha \pm \beta) = \cos(\alpha)\cos(\beta) \mp \sin(\alpha)\sin(\beta)$

* $S_{\alpha \pm \beta}$：
$\sin(\alpha \pm \beta) = \sin(\alpha)\cos(\beta) \pm \sin(\beta)\cos(\alpha)$

* $T_{\alpha \pm \beta}$：
$\tan(\alpha \pm \beta) = {{\tan(\alpha) \pm \tan(\beta)} \over {1 \mp \tan(\alpha)\tan(\beta)}}$

####  倍角
1. 二倍角
  * $S_{2\alpha}$：
    $\sin(2\alpha) = 2\sin(\alpha)\cos(\alpha)$
  
  * $C_{2\alpha}$：
    $\cos(2\alpha) = \cos^2(\alpha) - \sin^2(\alpha)$
  
  * $C_{2\alpha}^\prime$：
    * $\cos(2\alpha) = 2\cos^2(\alpha) - 1$
    * $\cos(2\alpha) = 1 - 2\sin^2(\alpha)$
  
  * $T_{2\alpha}$：
    $\tan(2\alpha) = {2\tan(\alpha) \over {1 - \tan^2\alpha}}$

2. $n$倍角
  * $S_{n\alpha}$：
    $\sin(n\alpha) = \begin{vmatrix} \sin(\alpha) & 0 & 0 & \cdots & 0 & 0 \\ 0 & 2\cos(\alpha) & 1 & \cdots & 0 & 0 \\ 0 & 1 & 2\cos(\alpha) & \cdots & 0 & 0 \\ \vdots & \vdots & \vdots & \ddots & 1 & 0 \\ 0 & 0 & 0 & 1 & 2\cos(\alpha) & 1 \\ 0 & 0 & 0 & 0 & 1 & 2\cos(\alpha) \end{vmatrix}$
  
  * $C_{n\alpha}$：
    $\cos(n\alpha) = \begin{vmatrix} \cos(\alpha) & 1 & 0 & \cdots & 0 & 0 \\ 1 & 2\cos(\alpha) & 1 & \cdots & 0 & 0 \\ 0 & 1 & 2\cos(\alpha) & \cdots & 0 & 0 \\ \vdots & \vdots & \vdots & \ddots & 1 & 0 \\ 0 & 0 & 0 & 1 & 2\cos(\alpha) & 1 \\ 0 & 0 & 0 & 0 & 1 & 2\cos(\alpha) \end{vmatrix}$

#### 半角
* $S_{\alpha \over 2}$：
$\sin({\alpha \over 2}) = \pm \sqrt{{1 - \cos(\alpha)} \over 2}$

* $C_{\alpha \over 2}$：
$\cos({\alpha \over 2}) = \pm \sqrt{{1 + \cos(\alpha)} \over 2}$

* $T_{\alpha \over 2}$：
$\tan({\alpha \over 2}) = \pm \sqrt{{1 - \cos(\alpha)} \over {1 + \cos(\alpha)}}$

* $T_{\alpha \over 2}^\prime$：
  * $\tan({\alpha \over 2}) = {{1 - \cos(\alpha)} \over \sin(\alpha)}$
  * $\tan({\alpha \over 2}) = {\sin(\alpha) \over {1 + \cos(\alpha)}}$

#### 积化和差
* $SC$：
$\sin(\alpha)\cos(\beta)={1 \over 2}[\sin(\alpha + \beta) + \sin(\alpha - \beta)]$

* $CS$：
$\cos(\alpha)\sin(\beta)={1 \over 2}[\sin(\alpha + \beta) - \sin(\alpha - \beta)]$

* $CC$：
$\cos(\alpha)\cos(\beta)={1 \over 2}[\cos(\alpha + \beta) + \cos(\alpha - \beta)]$

* $SS$：
$\sin(\alpha)\sin(\beta)=-{1 \over 2}[\cos(\alpha + \beta) - \cos(\alpha - \beta)]$

#### 和差化积
* $S + S$：
$\sin(\alpha) + \sin(\beta)=2\sin({{\alpha + \beta} \over 2})\cos({{\alpha - \beta} \over 2})$

* $S - S$：
$\sin(\alpha) - \sin(\beta) = 2\cos({{\alpha + \beta} \over 2})\sin ({{\alpha - \beta} \over 2})$

* $C + C$：
$\cos(\alpha) + \cos(\beta) = 2\cos({{\alpha + \beta} \over 2})\cos({{\alpha - \beta} \over 2})$

* $C - C$：
$\cos(\alpha) - \cos(\beta) = -2\sin({{\alpha + \beta} \over 2})\sin({{\alpha - \beta} \over 2})$

#### 万能
* $\sin(\alpha) = {2\tan(\alpha/2) \over {1 + \tan^2(\alpha/2)}}$

* $\cos(\alpha) = {{1 - \tan^2(\alpha/2)} \over {1 + \tan^2(\alpha/2)}}$

* $ \tan(\alpha)= {2\tan(\alpha/2) \over {1 - \tan^2(\alpha/2)}}$

#### 降幂
* $\sin^2(\alpha) = {{1 - \cos(2\alpha)} \over 2}$

* $\cos^2(\alpha) = {{1 + \cos(2\alpha)} \over 2}$

* $\sin(\alpha)\cos(\alpha) = {1 \over 2}\sin(2\alpha)$

#### 一角一函数
* $a\sin(\alpha) + b\cos(\alpha) = \sqrt{a^2 + b^2}\sin(\alpha + \varphi), \varphi = \arctan({b \over a})$


### 解三角形（待完成）
设$\triangle ABC$外接圆半径为$R$，内切圆半径为$r$
* **正弦定理**
  * ${a \over \sin(A)} = {b \over \sin(B)}={c \over \sin(C)} = 2R$
* **余弦定理**
    * $a^2 = b^2 + c^2 - 2bc \cdot \cos(A)$
    * $b^2 = c^2 + a^2 - 2ca \cdot \cos(B)$
    * $c^2 = a^2 + b^2 - 2ab \cdot \cos(C)$
* 推论：**射影定理**
  * $a = b\cos(C) + c\cos(B)$
  * $b = c\cos(A) + a\cos(C)$
  * $c = a\cos(B) + b\cos(A)$
    * *注意：大题不能直接用，遇到该形式的等式应优先使用正弦定理化成角的关系，或使用余弦定理化成边的关系*
* **正切定理**
  * ${{a + b} \over {a - b}} = {\tan({{A + B} \over 2}) \over \tan({{A - B} \over 2})}$
  * ${{b + c} \over {b - c}} = {\tan({{B + C} \over 2}) \over \tan({{B - C} \over 2})}$
  * ${{c + a} \over {c - a}} = {\tan({{C + A} \over 2}) \over \tan({{C - A} \over 2})}$

* **半角定理**
  * $\tan({A \over 2}) = \sqrt{{(s - b)(s - c)} \over {s(s - a)}} = {1 \over {s - a}}\sqrt{{(s - a)(s - b)(s - c)}\over s}$
  * $\tan({B \over 2}) = \sqrt{{(s - c)(s - a)} \over {s(s - b)}} = {1 \over {s - b}}\sqrt{{(s - a)(s - b)(s - c)}\over s}$
  * $\tan({C \over 2}) = \sqrt{{(s - a)(s - b)} \over {s(s - c)}} = {1 \over {s - c}}\sqrt{{(s - a)(s - b)(s - c)}\over s}$


**解法**：

| 已知条件 | 解法 |
|:-:|:-:|
| 两角，一边 <br> 如：$A, B, c$ | 1. $A + B + C = \pi$求$C$ <br> 2. 正弦定理求$a, b$ |


### 七 复数
#### 复数的概念
**虚数单位**：
* $\mathrm i$
* 它的平方等于$-1$，即$${\mathrm i}^2 = -1$$
* 实数与它进行四则运算时，原有的加、乘运算律仍然成立

**复数**：
* 形如$a + b{\mathrm i}(a, b \in \mathbb R)$的数
* 有序实数对$(a, b)$,其中$a, b \in \mathbb R$
* 所有复数构成的集合（复数集）记为$\mathbb C$：$$\mathbb C = \{a + b{\mathrm i} | a, b \in \mathbb R\}$$
* $\mathbb C$中的*加法*和*乘法*：$$\begin{matrix} (a + b{\mathrm i}) + (c + d{\mathrm i}) = (a + c)+(b + d){\mathrm i} \\ (a + b{\mathrm i}) (c + d{\mathrm i}) = (ac - bd) +(ad + bc){\mathrm i} \\ a, b, c, d \in \mathbb R \end{matrix}$$
* $\mathbb C$中的*减法*和*除法*：$$\begin{matrix} z_2 - z_1 = z_2 + (-z_1) \\ {z_2 \over z_1} = z_2({1 \over z_1})\\ z_1, z_2 \in \mathbb C \end{matrix}$$

**算数性质**：
* **交换律**：
  * **加法交换律**：$\forall z_1, z_2 \in \mathbb C, z_1 + z_2 = z_2 + z_1$
  * **乘法交换律**：$\forall z_1, z_2 \in \mathbb C, z_1 z_2 = z_2 z_1$
* **结合律**：
  * **加法结合律**：$\forall z_1, z_2, z_3 \in \mathbb C, (z_1 + z_2)+ z_3 = z_1 + (z_2 + z_3)$
  * **乘法结合律**：$\forall z_1, z_2, z_3 \in \mathbb C, (z_1 z_2)z_3 = z_1(z_2 z_3)$
* **单位元**：
  * **加法单位元**：$\forall z \in \mathbb C, z + 0 = z$
  * **乘法单位元**：$\forall z \in \mathbb C, 1z = z$
* **逆元**：
  * **加法逆元**
  * **乘法逆元**
* **分配性质**：
  * $\forall z_1, z_2, z_3 \in \mathbb C, z_3 (z_1 + z_2)= z_1 z_3 + z_2 z_3$

**分类**：
* 复数（$z$）
  * 实数（$\Im(z) = 0$）
  * 虚数（$\Im(z) \neq 0$）
    * 纯虚数（$\Re(z) = 0$）

**复数的模**：
$\left| z \right| = \sqrt{\Re^2(z) + \Im^2(z)}$

**共轭复数**：
$\bar z = \Re(z) - \Im(z)$

**形式**：
  1. 代数形式 $a + b{\mathrm i}(a, b \in \mathbb R)$
  2. 三角形式 $r[\cos(\theta) + {\mathrm i}\sin(\theta)], r \geqslant 0, 0 \leqslant \theta < 2\pi$
  3. 指数形式 $r{\mathrm e}^{{\mathrm i}\theta}, r \geqslant 0, 0 \leqslant \theta < 2\pi$

**复数相等**：
* $\Re(z_1) = \Re(z_2), \Im(z_1) = \Im(z_2) \Leftrightarrow z_1 = z_2$
* $\left| z_1 \right| = \left| z_2 \right|, \arg(z_1) = \arg(z_2) \Leftrightarrow z_1 = z_2$


### 补充：向量
设$\boldsymbol{a}=(x_a, y_a, z_a)$，$\boldsymbol{b}=(x_b, y_b, z_b)$，$\boldsymbol{c}=(x_c, y_c, z_c)$，则

1. 数量积／内积／点积：$$\boldsymbol{a} \cdot \boldsymbol{b} = \left | \boldsymbol{a}\right| \left | \boldsymbol{b}\right| \cdot \cos<\boldsymbol{a}，\boldsymbol{b}>=x_ax_b+y_ay_b+z_az_b$$
2. 向量积／外积／叉积：$$\boldsymbol{a} \times \boldsymbol{b} = \left | \boldsymbol{a}\right| \left | \boldsymbol{b}\right| \cdot \sin<\boldsymbol{a}，\boldsymbol{b}>= \begin{vmatrix} \boldsymbol{i} & x_a & x_b \\ \boldsymbol{j} & y_a & y_b \\ \boldsymbol{k} & z_a & z_b\end{vmatrix}$$
3. 混合积：$$[\boldsymbol{a}\boldsymbol{b}\boldsymbol{c}] = (\boldsymbol{a}\cdot\boldsymbol{b})\times\boldsymbol{c} = \begin{vmatrix} x_a & x_b &x_c \\ y_a & y_b &y_c \\ z_a & z_b & z_c \end{vmatrix}$$
4. 
5．

# 几何
## 立体几何
### 点、线、面的位置关系

**公理一：过不共线的三点有且仅有一个平面**

**公理二：**
简记：$A, B \in l, A, B \in \alpha \Rightarrow l \subset \alpha  \ $

**公理三：**
简记：$P \in \alpha, P \in \beta, \alpha \cap \beta = l \Rightarrow P \in l$

**公理四：（平行线的传递性）**
简记：$a \parallel b, b \parallel c \Rightarrow a \parallel c$

**推论一：过直线及这条直线外一点，有且仅有一条直线．**

**推论二：两条相交直线确定一个平面．**

**推论三：两条平行直线确定一个平面．**

### 第二章  多面体和旋转体
#### 一  多面体
##### 2.1．棱柱
棱柱的概念和性质

**棱柱**：由两个面互相平行，其余各面都是四边形[\^*]，并且每相邻两个四边形的公共边都互相平行，由这些面所围成的几何体叫做棱柱．
    
* **棱柱的底面**：棱柱两个互相平行的面．
  
* **棱柱的侧面**：棱柱其余各面．
  
* **棱柱的侧棱**：棱柱两个侧面的公共边．
  
* **棱柱的顶点**：棱柱侧面与底面的公共顶点．
  
* **棱柱的（体）对角线**：棱柱不在同一个面上的两个顶点的连线．
  
* **棱柱的高**：棱柱两个底面间的距离．

##### 2.2 棱锥

**棱锥**：底面是多边形，其余各面是有公共顶点的三角形，由这些面所围成的几何体叫做棱锥．

* **棱锥的**

## 平面解析几何

### 第一章 直线
#### 一 有向线段、定比分点
#### 直线的方程
#### 两条直线的位置关系

> 本节搭配。食用更佳哦！

设$l_1 : A_1x+ B_1y + C_1 = 0, \, l_2 : A_2x+ B_2y + C_2 = 0$

* **平行（不重合）**：$$l_1 \parallel l_2 \Leftrightarrow \begin{vmatrix} A_1 & B_1 \\ A_2 & B_2 \end{vmatrix} = 0$$

* **垂直**：$$l_1 \perp l_2 \Leftrightarrow A_1A_2 + B_1B_2 = 0$$

* 两条直线所成的角，简称**夹角**：$$
\left\{\begin{matrix}\sin \vartheta &=& {\left| \begin{vmatrix} A_1 & B_1 \\ A_2 & B_2 \end{vmatrix} \right| \over \sqrt{A_1^2 + B_1^2} \sqrt{A_2^2 + B_2^2}} \\ \cos \vartheta &=& {\left| A_1A_2 + B_1B_2 \right| \over \sqrt{A_1^2 + B_1^2} \sqrt{A_2^2 + B_2^2}} \\ \tan \vartheta &=& \left| {\begin{vmatrix} A_1 & B_1 \\ A_2 & B_2 \end{vmatrix} \over A_1A_2 + B_1B_2} \right| \end{matrix}\right.$$


### 附
1．**直线**方程
| 方程名称 | 方程 | 说明 |
|:-:|:-:|:-:|
| **一般式** | $Ax + By + C = 0$ | $A$, $B$不同时为零 |
| 点斜式 | $y-y_1=k(x-x_1)$ | $(x_1,y_1)$为已知点坐标，$k$为已知斜率，不能平行于$y$轴 |
| 斜截式 |||
| 两点式 | ${y - y_0 \over x - x_0} = {y_1 - y_0 \over x_1 - x_0}$ |  |
| 截距式 | ${x \over x_0} + {y \over y_0} = 1$ |  |

## 微积分初步
### 第一章  极限
##### 1.1  数列的极限
1．**极限**：一般地，对于一个无穷数列$\{a_{n}\}$，如果存在一个常数$A$，无论预先指定多么小的正数$\varepsilon$，都能在数列中找到一项$a_{N}$，使得这一项后面所有的项与$A$的差的绝对值都小于$\varepsilon$（即当$n > N$时，$\left| a_n - A \right| < \varepsilon$恒成立），就把常数$A$叫作**数列$\{a_n\}$的极限**，记作
    $${\lim_{n \to \infty} a_{n}=A．}$
    有时也可记作
    $${\mathrm 当\, n \to \infty \, \mathrm时，\, a_{n} \to A．}$

##### 1.2  数列极限的四则运算
1．$$
    \boxemathrm{如果} A, B, C \mathrm{是常数},\\
     \lim_{n \to \infty}a_{n}=A, \lim_{n \to \infty}b_{n} =B,那么\\
    \lim_{x \to \infty}
    \lim_{x \to \infty}
    \lim_{x \to \infty}}
    $$
### 第二章  导数和微分
#### 一  导数概念
#### 二  求导方法
#### 三  微分
### 第三章  导数的应用
#### 一  一阶导数的应用
#### 二  二阶导数的应用
### 第四章  不定积分
### 第五章  定积分及其应用
#### 一  定积分的概念和计算
#### 二  定积分的应用
### 附表  简易积分表
1．$\int \, {\rm d}x= $
