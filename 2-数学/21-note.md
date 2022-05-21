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

------

# <center>英语</center>

## 语法知识

## 单词

### 外貌特征

#### <u>apply</u>

#### <u>average</u>

#### <u>dress</u>

#### <u>expression</u>

#### <u>figure</u>

#### <u>fit</u>

------

#### age

#### aged

#### appearance

#### attractive

#### blank

#### boot

#### build

#### button

#### clothing

#### dark

#### doubtful

#### elderly

#### fair

#### fashion

#### feature

#### glove

#### heavy

#### ring

#### serious

#### top

#### wear

#### yong

------

## 完形填空

### 高考

### 模拟

### 报纸
1. 
    | 第一期 |     A.     |    B.     |     C.     |      D.       |
    | :----: | :--------: | :-------: | :--------: | :-----------: |
    |   1.   |  planning  |  knowing  | forgetting | understanding |
    |   2.   |   matter   |   drop    |    test    |     show      |
    |   3.   |  valuable  | difficult | enjoyable  |    tiring     |
    |   4.   |  teachers  | students  |  seniors   |    juniors    |
    |   5.   |   common   |   good    |   simple   |    strict     |
    |   6.   |   misses   |   loves   |  regrets   |   remembers   |
    |   7.   |  special   | required  |  popular   |   organised   |
    |   8.   |     so     |    if     |    but     |    because    |
    |   9.   |    easy    |   free    |    busy    |     local     |
    |  10.   |  control   |  humour   | direction  |  confidence   |
    |  11.   |    Labs    |   Shops   | Bathrooms  |  Restaurants  |
    |  12.   |    late    |  afraid   |    hurt    |     lost      |
    |  13.   | playground | classroom |  building  |    campus     |
    |  14.   |    open    |   solve   |  achieve   |    collect    |
    |  15.   |    tour    |  attend   |   change   |    choose     |

***

2. 
    | 第二期 |      A.      |      B.      |    C.     |      D.       |
    | :----: | :----------: | :----------: | :-------: | :-----------: |
    |   1.   |   welcomed   |   confused   | attracted |    trained    |
    |   2.   | looked after |  laughed at  | accepted  |  remembered   |
    |   3.   |    tired     |  unpopular   |   hurt    |    anxious    |
    |   4.   |    action    |    words     |   plans   |   solution    |
    |   5.   |     bus      |     boat     |   bike    |     train     |
    |   6.   |    driver    |    friend    |  teacher  |   stranger    |
    |   7.   |   nervous    |   curious    | addicted  |   impressed   |
    |   8.   |   sadness    |    debate    |  excuse   |   adventure   |
    |   9.   |   achieve    |     need     |  regret   |     quit      |
    |  10.   |     left     |   arrived    |  turned   |    stopped    |
    |  11.   |    hurry     |    while     |  circle   |      way      |
    |  12.   |   shouted    |   searched   |  knocked  |     stood     |
    |  13.   |    sport     | cheerleading |  school   |     dream     |
    |  14.   |   hopeful    |   thankful   | important |     sorry     |
    |  15.   |    habits    |   thoughts   | interests | personalities |




 ## 周测


| 周测一 |     A.     |    B.     |     C.     |     D.     |
| :----: | :--------: | :-------: | :--------: | :--------: |
|   1.   |  stopped   |  replied  | recovered  |    won     |
|   2.   |  serious   |  careful  |  anxious   | frightened |
|   3.   |   wasted   |   spent   |  counted   |   missed   |
|   4.   |   father   |  friend   |   sister   | classmate  |
|   5.   |   funny    |  unhappy  |   close    |    poor    |
|   6.   |  changed   |  started  |   failed   | continued  |
|   7.   |   Though   |   When    |  Because   |   Unless   |
|   8.   | difficult  |  common   | convenient | important  |
|   9.   | talk about |  give up  |  look for  | take down  |
|  10.   |   school   |   home    |    work    |    play    |
|  11.   |  discover  |   trust   |    love    |   watch    |
|  12.   |    way     |   story   |    job     |    life    |
|  13.   |  nothing   | something |  anything  | everything |
|  14.   |   saved    |  shaped   | protected  | persuaded  |
|  15.   |   admin    |  explain  |  consider  |   prove    |

------

|      |      A.      |     B.      |     C.     |     D.      |
| :--: | :----------: | :---------: | :--------: | :---------: |
|  1.  |     read     |   deserve   |    have    |    hear     |
|  2.  |    friend    |   family    |  teacher   |  neighbour  |
|  3.  | breathtaking |   boring    |   moving   | frightening |
|  4.  |     time     |   feeling   |    view    |     way     |
|  5.  |    smiled    |  continued  | hesitated  |   repeat    |
|  6.  |   sliding    |  standing   |  jumping   |   running   |
|  7.  |   imagined   |   risked    |  avoided   |    kept     |
|  8.  |     edge     |    peak     |   inside   |   surface   |
|  9.  |     sink     |     fly     |    die     |    shout    |
| 10.  |     high     |     low     |   steady   |   limited   |
| 11.  |    press     |   strike    |   touch    |    push     |
| 12.  |    aching    |   healing   |   racing   |   crying    |
| 13.  | occasionally |   quickly   |  usually   | eventually  |
| 14.  |   pointing   |  screaming  |  laughing  |   aiming    |
| 15.  |  adventure   |   flight    | experiment |   voyage    |
| 16.  |    wings     |    hands    |  warnings  |   spirits   |
| 17.  |   forgive    |  convince   |  believe   |    doubt    |
| 18.  | put up with  | leave aside |  run into  | get out of  |
| 19.  |    story     |   promise   |   speech   | declaration |
| 20.  |    write     |    share    |  publish   |   record    |

------

|      |     A.     |     B.     |      C.      |     D.      |
| :--: | :--------: | :--------: | :----------: | :---------: |
|  1.  | regretted  | remembered |  cancelled   |  suggested  |
|  2.  | satisfied  |  careful   |   prepared   |    known    |
|  3.  |   rested   |   worked   |   searched   |   shopped   |
|  4.  |  avoided   | continued  |    forgot    | recommended |
|  5.  |   found    | prevented  |    joined    |    saved    |
|  6.  |    bad     |  promise   |    change    |    taste    |
|  7.  |  visiting  |   paying   |    trying    |   moving    |
|  8.  |  go ahead  |  keep up   |   show off   | turn aside  |
|  9.  |   cheap    |    real    |     free     |    fresh    |
| 10.  | creativity |  courage   |   honesty    |  kindness   |
| 11.  |   chose    |    left    |    owned     |   noticed   |
| 12.  |  allowed   |   helped   |   invited    |   taught    |
| 13.  | experience |  decision  | relationship |  schedule   |
| 14.  |   pride    |  sadness   |    doubts    |   thanks    |
| 15.  |   agree    |    ask     |     want     |    wait     |

------

| 周测二 | A. | B. | C. | D. |
|:-:|:-:|:-:|:-:|:-:|
| 1. | adults | referees | parents | educators |
| 2. | merely | barely | usually | freqenty |
| 3. | nature | resources | connection | behaviors |
| 4. | like | feed | teach | protect |
| 5. | disconnect | hear | learn | seperate |
| 6. | lead | time | charge | picture |
| 7. | rest | grow | eat | defend |
| 8. | good | awful | unique | strange |
| 9. | nobody | anybody | everybody | somebody |
| 10. | insisted | become | except | understood |
| 11. | well-rounded | former | enthusiastic | fresh |
| 12. | gone | exhausted | reserved | respected |
| 13. | progress | remain | collapse | disappear |
| 14. | give up | hold up | think about | talk about |
| 15. | mark | promise | presentation | difference |

------

# <center>物理</center>
## 引言——怎样学好物理知识
### 做好物理实验
1. 我们必须充分重视实践在学习物理知识中的重要意义，特别是要认真做好实验
2. 实验能够帮助我们形成正确的物理观念，增强观察物理现象和分析物理问题的能力，加深对物理规律的理解
3. 如何做好物理实验
    1. 实验前
    2. 
        * 明确实验目的
        * 弄懂实验原理
        * 了解所用仪器性能
        * 清楚实验步骤
    2. 实验中
        * 认真观察现象
        * 仔细记录必要的数据
    3. 实验后
        * 分析所得数据
        * 作出合理结论
    4. 其他
        * 手脑并用
        * 观察老师的演示实验
        * 在老师的指导下分析观察到的现象
        * 在课外多做简易实验

注：**物理实验**与**课外实验**单独成章
### 学好物理概念和规律

### 做好练习

（这一点也适用于其他学科）

1. 认真做好练习，可以加深对所学知识的理解，发现自己知识中的薄弱环节而去有意识地加强它（每节节末均有**高考真题**和**日常错题**），逐步培养自己的分析解决问题的能力，逐步树立解决实际问题的自信心
2. 做题步骤
    1. 仔细审题，弄清题意
    2. **根据题意、已知条件、所求答案来确定应该使用的物理规律**
    3. 利用这些规律来建立已知条件和所求答案之间的关系，求出合理答案
------
## 曲线运动
3. **曲线运动**：物体的运动轨迹为曲线的运动。
4. **方向**：质点在某一点/时刻的速度看向沿曲线上这一点的切线方向
5. **性质**：在曲线运动中，速度的方向是不断变化的，由于速度是矢量，既有大小，又有方向，所以曲线运动一定是变速运动
6. * 当加速度$a$恒定时为匀变速曲线运动
    * 当加速度$a$变化时为非匀变速曲线运动


1. **条件**:
    1. **幼力学**:合力$F-合事方向与速度本V$方向不共线.
        * 初速度$v_0$不为零
        * 合力不为零
        * 合力方向与速度方向不共线
    2. **运动学**:加速度$a$与速度方向不共线.

2. 简单运动的分类：

| $F(a)$与$v$的方向 | 轨通特点 | 加速度特点 | 运动性质 |
|:-:|:-:|:-:|:-:|
| 共线 | 直线 | 恒定 | 匀速直线运动 |
| 共线 | 直线 | 不恒定 | 非匀速直线运动 |
| 不共线 | 曲线 | 恒定 | 匀速直线运动 |
| 不共线 | 曲线 | 不恒定 | 非匀速直线运动 |

### 天体运行 
$$F_n = ma_n = m\omega^2r = m{v^2 \over r} = m{4\pi^2 \over T^2}r=G{Mm \over r^2} \\
\Rightarrow \left\{
\begin{matrix}
a_n = \omega^2r = {v^2 \over r} = {4\pi^2 \over T^2}r=G{M \over r^2} \\
\omega = \sqrt{a_n \over r}
\end{matrix}
\right.
$$
$$mg = G{Mm \over R^2}$$


### 功
1. $W = F l \cdot \cos(\alpha)$
2. 物理意义：功率是表示做功快慢的物理量．
3. * 定义：功$W$与完成这些功所用时间的比值．
    * 定义式 $ P = {W \over t}$
4. 单位：在国际单位制中，功率的单位是**瓦特**，简称**瓦**，符号是$\mathrm{J}$
5. * $1\mathrm{W}=1 \mathrm{J \over s}$
    * $1 \mathrm{kW} = 10^3 \mathrm{W}$
6. $P = {W \over t} = {Fl \over t} = Fv$
7. 机车启动
   * $P$恒定
     * $P = Fv \rightarrow F={P\over v}\rightarrow F - f = ma \rightarrow a=0$
     * $\boxed{v_M = {P \over F} = {P \over f}}$
     * $ \boxed{{p \over v} - f = ma}$
   * $a$恒定
     * $\boxed{P = Fv = Fat \rightarrow t={p \over Fa}}$
     * $\boxed{Pt - fx = {1 \over 2} mv^2}$（动能定理）

------

# <center>化学</center>

## 元素化学

1.工业上除$\ce95023$
1.$\ceqSO2+CaCO3 I>CaO+SO2→CaCO3 Case
2. $\ce{NH3*+12O→（NH4)3SO3-HNOS→（NH4)2S043$
3. $ lce 9502+ Fe2 (SO4) 3- > FeSO, H2SO4
2.常见氧化剂/还原剂
*氧化剂：
*离子：$\ce{Fe3+,CLO-,MnO4-,H++NO3-3
* 分子：$/ce{H2SO4(浓）,O2,CL2,H2O2,Na2O23$
*还原名：
X禽子：$\ce{Fe2+,S2-,SO={33^{2-},I-3$
*分子：$\ce9H2S,SO23$
* *主意：书ce9fe2+,Fe3+3$55\ce{H2SO4(WR),SO23$之间不能反应*

## 有机化学

1. 有机物的性质特点
    * 溶解性（相似相溶原理）
    * 非电解质，不导电，溶、沸点低（共价键，共价化合物）
1. 成键特点（$\ce{C}$）
    * 成键数目：$4$个共价键
2. 成键方式
    * $\ce{C \bond{1} C}$单键（$\sigma$键）
    * $\ce{C \bond{2} C}$双键（$\sigma$键和1个$\pi$键）
    * $\ce{C \bond{3} C}$三键（$\sigma$键和$2$个$\pi$键）

------

# <center>生物</center>

##性状类
1.烟对性状（relative trait)**:
*一种*生物的同一种*性状的*不同大表现类型
2. **星性性状**:
具有相对性状的结合素本杂交，F表现出来的性状
3.**隐性性状**;
具有相对性状的结合系本亲交，F，未表现出来的性状
4.*米性状兮离**:
亲种后代中同时出现量性性状和隐性性状的现象##个体类
1.遗传统合子兴兴：
遗传因子组成相同的个体.
2.**杂合子**
遗传回子组成不同的个体
3.**基因**;
生物的性状是由基因决定的.
4. **表现型/表型（phenotype)**:
生物体表现出来的性状
5.**基因型（genotype)**:
与表型有关的基因组成
##基因类
1. **星性遗害
决定是性性状的基回，用大写字母来表示
2.**隐性基因**:
决定隐性性状的基因，用小写字母来表示
3.**等位基因（allele)**:
控制相对性状的基因
4.**非-
:**...
不同
5.**相等
、、
6.孟德尔遗传规律精情：
生物体遗传的不是性状本身，而是拉制性状的遗传因子。
7.*分离定律**:
在生物的体细胞中，控制同一性状的遗传因子成对存在，不相融合；在形成配子时城对的遗传因子发生分离火，分离后的遗传因子分别进入不同的配子中，随配子遗传给后代.

## DNA :dna:

1. 在双链DNA中
    * A=T，G=C
    * $A\mathrm{A+G=T+C=A+C=T+G={/\over2f(A+T+C任意两不互补碱基数量之和为全部碱某数量一半.
    **{{A+G} lover{T+C3}={{A+C}\over{T+C}}}=1$
2. 在双链DNA兮子中，${{A+T}\over{G+(333本在不同DNA分子中比值不同，体现了不同生物DNA分子的特异性
3. 在双链DNA中，$33A+T3\over{A+T+G+C33=...$
4. 有双链DNA中，若书行A，1+T-1310ver9G-1+C-133=m$则$---2=m$，$...=m$
=n
则书......2=31 lover n3 $ +...=1$
5. *补则等，不补则倒.*
6.
$A-1+T-1=A-2+T-2=10ver23(A+T)
7. $9AH lover {A-1+T-1+C-1+G-133 3/3/3/3/1+ G-133 3/1+ C-1+{A-1\over {A+T+C+G33=9b lover 23
*

------

# <center>政治</center>

------

# <center>历史</center>

------

# <center>地理</center>

## 人口

### 人口分布

#### 世界人口的分布

1. 分布
    1. 是
    2. 是
    3. 
2. 四大人口稠密区：
3. 特点：极不平衡

#### 影响人口分布的因素自然因素

1. 自然因素
    1. 气候
    2. 地形
    3. 水源
2. 人文因素
    1. 生产力水平
        1. 农业社会
        2. 工业社会
    2. 经济发展水平
    3. 历史因素
1. 其他因素：政治、军事、文化

#### 中国的人口分布

### 人口迁移

#### 是什么

1. 人口迁移
2. 人口机械增长
3. 影响

#### 为什么

1. 动力（推拉理论）
2. 自然因素
    1. 气候
    2. 水源
    3. 土壤
    4. 资源
    5. 自然灾害
3. 人文因素
    1. 经济
    2. 其他：政治、军事、文化

#### 时空特点

##### 国际

1. 19c.以前
2. 19c.~20c.上半叶
3. 二战以后

#### 国内

1. 工业化以前
2. 工业化以后

### 人口容量

#### 区域资源环境承载力

1. 是什么
2. 因素：
    1. 自然资源状况
    2. 社会经济和科技发展水平
    3. 人均消费水平

#### 人口合理容量

1. 是什么
2. 意义
3. 原因
4. 措施



