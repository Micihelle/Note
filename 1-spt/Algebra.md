抽象代数motivation:
第一个是从代数方程的解法到Galois理论；第二个是从Fermat大定理到代数数论的建立；第三个是从不变量理论到Hilbert定理。你按这三条线去读历史，自然会了解所有抽象代数概念和定理的由来


## Algebra-DIY
- Axler Sheldon, Linear Algebra Done Right (Third Edition)

how to imagine a physical space of four  or more dimensions
- 《Flatland:A Romance of Many Dimensions》by Edwin A. Abbott

n维向量：“方向”、“大小”概念的进一步抽象
EX 1.A 04-06
the definition of complex numbers (be descirbed by the  ordered pair of real numbers (a,b) and some fundemental propetries)如何描述一个complex numbers
- the definition of `list`,`length` (Many mathematicians call a list of `length` n an n-tuple)
- A list of length n is an ordered collection of n elements (which might be numbers, other lists, or more
abstract entities)

EXERCISES 1.A：
``` EXERCISES 1.A
...
07:分析学方法证明加法逆单位元的存在
08:分析学方法证明乘法逆单位元的存在
(为什么这里只解释一个分析学方法呢，因为觉得把数学当成一个整体会更好一点)
09:乘法分配律成立
10:代数方法
11：代数方法
12：加法交换律成立
13：乘法交换律成立
14：乘法逆单位元的存在
15：....
```


1.B：Definition of Vector Space
- motivation：properties of addition and scalar multiplication in $F^n$ -> **于品数学分析讲义中对空间的观点:配备了某些结构的集合$X$**
	- 为什么需要把在$F$中拥有的properties "推广"到 Vector Space 中去呢（给向量空间配备加法结构和乘法结构
	- $\alpha+\beta=\beta+\alpha\mathrm{~and~}\alpha\beta=\beta\alpha\text{ for all }\alpha,\beta\in\mathbf{C};$ 
	- $u+\nu=\nu+u\mathrm{~for~all~}u,\nu\in V;$
- addition in Vector Space
- scalar multiplication in Vector Space 
- the definition of Vector Space
	- The simplest vector space contains only one point. In other words, $\{0\}$ is a vector space.

Apply 1.23 to 1.24 Example:
- 1.$\text{If S is a set, then F}^S\text{ denotes the set of functions from S to F}.$(包括了各种函数关系)
- 2.

加法单位元唯一性证明：假设等式两边存在不同的加法单位元->交换律
加法逆元存在且唯一的证明：..

 scalar multiplication：需要从两种角度来理解这种运算，一种是数的角度，一种是向量的角度
 - 1.29 The number 0 times a vector -> the product of the scalar 0 and any vector equals the vector 0
 - 1.30 A number times the vector 0 -> the product of any scalar and the vector 0 equals the vector 0.

V：vector space exist the additive identity -> 0v (v属于$V$)(有没有更加自然的从数域的概念过渡到向量空间的概念的思路呢？)
EXERCISES 1.B
``` EXERCISES 1.B
1. -> 加法逆单位元存在且唯一 Unique additive inverse(可参考1.25 Unique additive identity的证明方法：加法交换律成立、加法单位元存在且唯一)
2.数与向量的点乘  
-> 1.29 The number 0 times a vector:the product of the scalar 0 and any vector equals the vector 0 
-> 1.30 the product of any scalar and the vector 0 equals the vector 0.
-> 其他导致点乘结果0的情况？(已经包括了any scalar、any vector的组合情况)

```

3.向量与向量之间的“连通路径”存在且唯一
- 向量的表示 ：x exists -> associativity
- exists a unique $x\in V$   -> like the proof of 1.25  Unique additive identity,1.26 Unique additive inverse

```
4.empty set is not a vector space:
-> the definition of vector space
```

## 线性代数学习


**将线性代数和空间解析几何作为一个整体**
“具体—>抽象—>具体”：
> 从许多具体的例子中抽象出某个概念；然后通过代数的方法对这一概念进行研究，得到一般的结论；最后再将这些结论返回到具体的例子中，得到各种运用。

学习方法：理解几何意义，掌握代数方法
>我们可以通过具体的例子去理解抽象的定义和证明；我们可以将定理的结论运用到具体的例子中，从而加深对定理的理解和掌握

**知行合一**：**“The best way to learn Mathematics is to do Mathematics”**
**学习思路：** 
1.听一遍丘维声的课 -> 
2.看完一遍《线性代数这样学》边看边刷对应章节的题  or 高等代数学教材-> 
3.高等代数指导书 + b站习题课视频- >
4.《复旦大学高等代数习题集》+谢老师博客
学习材料见:[复旦大学高等代数课程学习资料推荐 - torsor - 博客园 (cnblogs.com)](https://www.cnblogs.com/torsor/p/4731153.html)


自我push！：白皮书上难题的证明思路是怎样想出来的，还有其他的证明吗？


**高代白皮书学习指南**：

**高等代数教材**:   
知识体系可见：[谢启鸿细说复旦大学高等代数教材 - torsor - 博客园 (cnblogs.com)](https://www.cnblogs.com/torsor/p/17581459.html))
“线性方程组的求解”的工具：行列式 -> 矩阵 ->  线性空间
- 从矩阵到行列式：
- 从行列式到矩阵：
- 从矩阵到线性空间
线性空间：从行列向量空间到线性空间
线性映射：线性映射与矩阵的一一对应关系
多项式：行列式与多项式的关系
特征值：从一维不变子空间到特征值和特征向量
**相似标准型**：后面几章有点小难，看不太懂理论引入的动机

**高等代数中的的三大问题？**


因为我是一个很喜欢问为什么，想带着好奇心解决问题的人，在这一点上数学是最能满足我的学科，所以我后面会思考成为一名数学研究者的主要矛盾是什么：能看懂顶刊的基础知识、人事关系、薪资待遇等等


## 前言：学习目标、主要问题

研究方向：
代数数论、解析数论、代数几何、微分几何、代数拓扑、微分拓扑


> 行列式、矩阵、线性空间这些东西到底是针对什么的抽象？
- 行列式的定义是如何抽象而来的：消元法(多维线性方程组的变元的系数)
- 矩阵的乘法是如何定义的：变量替换的思想

### 代数研究对象 

代数学中的问题：解n元线性方程组

线性空间
线性映射：相似、旋转、压缩
度量：既要考虑长度 又要考虑角度
双线性函数：（内积) 
用以描述具有度量的线性空间，比如欧几里得空间、

与度量有关的线性变换：正交变换、对称变换..

**高等代数课程研究对象：**
- 线性代数
	- 线性空间与线性映射
- 一元(或n元)多项式环的结构及其通用性质

#v 什么是一元多项式环：


伽罗瓦的证明：一元高次方程的求根问题 引入了域的概念、群的概念

近世代数：从研究根式求解 到 研究代数系统的结构、运算的映射

#v 从n元线性方程组到n维向量空间是怎么来的？

哪些思维方式需要拉满：（学数学的动机）
- 观察客观现象(纷繁复杂)：提出好问题,**数学是自然的**;抓住主要特征 比如从n元线性方程组到n维向量空间是怎么来的
- 抽象出概念或建立模型
- 探索：直觉与灵感、类比、归纳、联系、推理、分析、综合
- 猜测可能存在的规律
- 论证：分析、概念定义的运用、公理、已经证明的定理、逻辑推理
- 揭示事物的内在规律(井然有序)



#idea 
线性方程组的解与行列式的关系：
1.出发点还是更加侧重n元线性方程组的解 ,
对于几何的角度理解不够充分（维度与解的关系？)
-> 《空间解析几何》

2.线性方程组有唯一解 系数矩阵A的行列式不等于0

二阶行列式的几何意义：**向量所长成的图形(空间)的定向面积**
所谓定向：向量到向量的旋转方向
三阶行列式的几何意义：平行六面体的定向体积


3.线性方程组具有唯一解是否对应某一空间由**向量表示唯一**

#v 4.Laplace定理：
- 为什么行列式可以按任意行(列)展开
- 以及行列式各种的定义

### 08 N阶行列式
1.从矩阵到行列式：（由原方程组的系数矩阵所决定)
- 矩阵的意义：做增广矩阵 化行阶梯型矩阵来解线性方程组；


**2.为什么需要专门引入行列式，矩阵为什么不够用？**
- 从向量和向量空间的角度来考虑矩阵和行列式的区别：
- 从行列式到矩阵：
- 解的情况的判定


3.n元排列 
在n元排列中介绍“逆序数”的概念:
考虑行列式元素中的各种组合情况、记组成逆序数对的数目为逆序数、当逆序数为奇数时这对排列为奇排列，反之为偶排列。**(怎么数逆序数？-> n元排列的n!项中构成逆序的总数)**
这样定义逆序数来描述排列情况有什么意义呢?跟前面的高斯消元有什么联系呢？：
定理1：**对换是否会改变排列的奇偶性**：要么奇变偶、要么偶变奇 -> 确实会影响排列的奇偶性
- -> 直接考虑相邻对换的情形
- -> 在一般情况下直接考虑相邻对换
	- 奇数次的相邻对换
	- 偶数次的相邻对换
- **排列中发生任意位置的元素的交换，逆序数要怎么变？(直接*-1）**(难道不是既可能变成奇排列，也能变成偶排列吗)
	- 从自然序开始发生任意对换 ->(对于行列式的性质x的证明)（j+k+2)
- 一些引例：从任一n元排列经过一系列的对换互变至自然序排列，所做的对换次数与该n元排列具有相同的奇偶性  （逆序数直接等于经过对换变回自然序排列所进行的对换次数?）(一些等效的对换过程)
- **如何用逆序数来定义行列式的值**
	- **行列式的值与解的情况的判定:**


4.N阶行列式的定义：利用代数和来定义 -> 借助"n元"排列的概念来描述每一项为正还是为负
利用高斯消元法解线性方程组、利用代数和来定义行列式的值
思考排列组合（n！）的情况 -> 什么情况下为

5.行列式的性质
- 证明转置厚不变： 展开+代数余子式
- 矩阵的转置、矩阵转置过程中：元素是如何进行交换的？(如果分为行指标的交换和列指标的交换吧，对于矩阵整体而言是否存在一个最小、最大交换次数)
- 发生某初等行变换(两行互换）以后，行列式的值取负 -> (需要对排列中的元素做对换，逆序数发生了改变)
- 发生某初等行变换之后，行列式的值的变化
- **几何角度考虑行列式的性质与行列式的值**

6.  （014-19：22)

### 017 行列式的几何意义

从n维线性方程组的解到行列式：分析线性方程组的解的情况，然后定义行列式和行列式的值与对应的解的情况的映射关系(判定规则)，用代数方法解决(几何)问题和解方程的问题

维数?->在行列式中取到元素、(找到空间向量)
行列式的值：将行列式按(任给k)行按(任给k)列展开
(Laplace定理)引入k阶行列式和余子式的概念,然后用代数余子式的和来表示行列式的值
**(Laplace定理的证明：**
- 在只考虑按行按列展开的情况下，怎么考虑到代数余子式的系数?

二阶行列式几何意义：3行2列的行列式怎么处理 -> 有意义?
三阶行列式的几何意义：从几何的角度是否只有无解、有唯一解、有无穷解的情况，从行列是的角度只能分别是否有解。无解的情况对应的几何结构有哪些?
三阶行列式的展开：







### 019 线性空间与线性映射

为什么要进行这一步的抽象？：万里长征才走了第一步
为什么需要从3维推广到n维空间：**解n维线性方程组**

n维有序数组 <=> n维空间向量


我突然想到了黑格尔，能够广泛地吸收当时人类智慧的至高结晶，所以才能建立起一个更加大一统的形而上学，
而后来的哲学越是研究反倒越是能证明哲学作用的有限性，现在这个时代很难再出现全才通才了吧


#v  为什么多维空间一定存在？如何想象多维空间:
某种变化、linear transform（想象从1维到2维 2维到3维的线性变换）
#v 是不是一定存在无穷多维的空间呢（严谨版的证明）、为什么非欧空间一定存在？：


数学是自然的：集合和映射(满足某种对应法则)
映射中的定义域和陪域(脑海里面知道有这么个东西 但是没想过给它起个名字)

笛卡尔积：有序元素对的集合
代数运算：看成 $S*S$(笛卡尔积）到空间S上的一个映射
线性空间的定义：满足8条运算法则


### 020 线性空间的性质
### 066 多项式
“因式分解”：
“多项式”：表达式




## 一些想法


