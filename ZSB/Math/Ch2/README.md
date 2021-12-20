> [toc]
>
> 



```
数学学到什么程度可以进行下一部分的学习了
	“重要的是你愿意承认前面有没学懂的东西，还能心平气和地回去学懂。”

参考:

​	宋浩专升本课程
​	樊顺厚高等数学
​	河南专升本红皮书
​	同济高等数学   

TODO
	泰勒公式,微分中值定理

	
```



​                                       

# 第二章 一元函数微分学及其应用

## 1.1 导数定义





```
导函数: 对一个函数求导所产生的函数
Ex. y=x^2 导函数为y=2x
```



![image-20211218111009943](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211218111009943.png)





>x0为初始点的位置, (△x+x0)为变换后的位置 //△x为x0的增量(或改变量)
>
>相应的△y=f(x0+△x)-f(x0)

于是得到第一个导数公式

![image-20211208151414855](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208151414855.png)

令**x=x0+△x**,得到第二个导数公式

![image-20211208151640903](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208151640903.png)



导数you多种表示方法

![image-20211208152023962](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208152023962.png)

用第一导数公式求导,可推导出后面要学的导数公式

![image-20211208152709578](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208152709578.png)





<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208154057791.png" alt="image-20211208154057791" style="zoom:50%;" />



> 极限: 极限存在与该点处是否有定义是否相等无关
>
> 连续: 极限存在且与点函数值相等
>
> 可导: 可导必定连续

### 1.1.2左导右导

可导充分必要条件是左导数右导数存在且相等.

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208154718683.png" alt="image-20211208154718683" style="zoom:50%;" />

```
一般用于分段点的可导性
```

> Ex1. f(x)=|x|,在x=0处可导性

![image-20211208155118212](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208155118212.png)



### 1.1.3 可导 连续



可导一定连续,连续不一定可导

```
Ex1. 判断f(x)=立方根(x)在x=0处的连续性于可导性
```

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208162246951.png" alt="image-20211208162246951" style="zoom:50%;" />

### 1.1.4 几何意义

导数=过点切线的斜率,可导代表着光滑smooth

>切线:
>
>​	K=f'(x0)
>
>​	y-y=k(x-x0)
>
>法线(normal line): 他是条垂直于K的线
>
>​	切*法=-1
>
>​	法线= -(1/切)
>
>



```
Ex1. 已知y=x^2 球曲线(2,4)处的切线方程 法线方程

```

![image-20211208160510367](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208160510367.png)

未化简... 化简为x+y=0

### 1.1.5 导函数奇偶性质

x=偶函数, f'(x) = 奇函数

x=奇函数, f'(x) = 偶函数



## 1.2 ※ 导数公式

### 1.2.1 导数公式

这部分公式非常重要,就像乘法表你不会背的话肯定不会很方便. 所以你可以将每一个常用的导数公式用导数第一二公式分别推导一下加深记忆,再做题会好很多.

关于推导的视频可以看下 樊顺厚的p0202章节 20min往后的推导

> e^x的导数永远是e^x
>
> ​	(1/x)'=- 1/(x^2)
>
> ![img](https://gitee.com/quanlongcs/pic-bed/raw/master/img/0F087811.png)

![image-20211208185342866](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208185342866.png)

### 1.2.2 四则运算法则

![image-20211208185408446](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208185408446.png)

> 特别的如果是3项求导
>
> ​	(uvw)' = u'vw + uv'w + uvw'
>
> 如果是常数
>
> ​	(Cu)'=C * u'

### 1.2.3 复合函数

> 洋葱法则,不好说具体反正就是从外网内拆开求导. 多做几道题就懂了



![image-20211208190405034](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208190405034.png)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208192404429.png" alt="image-20211208192404429" style="zoom:50%;" />



![](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208194910206.png)



-



## 2.1 高阶导数与特殊函数导数

### 2.1.1高阶导数



> 高阶导数就是求多次导...
>
> 唯一变化是书写方式的变化
>
> 超过3阶导就要把相应的'替换成n

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208200741156.png" alt="image-20211208200741156" style="zoom:50%;" />





<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208202550799.png" alt="image-20211208202550799" style="zoom:50%;" />







### 2.1.2隐函数

> 同时对两边x进行求导建立y'的方程
>
> ​	注意的是每一个y对其求导时他不是单单一个y而是一个复合函数(关于y=f(x))的复合函数所以应该就可以理解为什么这样做题

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208203605662.png" alt="image-20211208203605662" style="zoom:50%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208204815707.png" alt="image-20211208204815707" style="zoom:50%;" />







发现红宝书这本的例题狗的很一个个复杂要死.



#### 2.1.2.1 对数求导法

>y=x^x 不能判断使用指数法则或是幂函数法则1所以使用对数1



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208211232903.png" alt="image-20211208211232903" style="zoom:67%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211218163649827.png" alt="image-20211218163649827" style="zoom:50%;" />







### 2.1.3由参数方程确定函数的导数

通过对t的求导来连接起来

> 要注意一点是y/x,不要颠倒顺序

![image-20211208205550736](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208205550736.png)



![image-20211208210031645](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208210031645.png)





> Ex.
>
> 参数方程的二阶导数 = (一阶参数方程)' / (dx/dt)'
>
> ![image-20211218151500421](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211218151500421.png)











#### 参数方程求切线

用题目给出的参数方程求导,带入给出的切点. 导数就是K

再把切点带到原函数参数方程得到(x,y)

化简得到切线方程





判断函数是否连续,已知可导必连续.进而判断可导性

![image-20211208212852599](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208212852599.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208212742464.png" alt="image-20211208212742464" style="zoom:80%;" />









### 2.1.5 反函数求导

> dy/dx -> dx/dy
>
> 导数的倒数

```
y=3x+1的导数 
	y' = 3
反函数y = (x-1) / 3
	y-1' = 1/3

```

 

## 3.1微分

### 3.1.1 微分



> 微分就是导数与dx的乘积
>
> dy=f'(x)dx

函数可微必可导,可导必可微



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208213547039.png" alt="image-20211208213547039" style="zoom:67%;" />

通过一些例题看一下微分是多么easy

![image-20211208214322970](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211208214322970.png)

可能唯一要注意的是写dx的时候写清楚:)



### 3.1.2 微分在近似值的应用

> 已知y=f(x),求f(A)的近似值
>
> 令A=x0+△x 则f(A)=f(x0+△x)+f'(x0)*△x
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211219165439599.png" alt="image-20211219165439599" style="zoom:67%;" />
>
> 









## 4.0 微分中值定理及洛必达法则





![image-20211219175503293](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211219175503293.png)

### 一 微分中值定理

#### 0 零点定理

> [a,b]连续
>
> f(a)*f(b)<0
>
> 至少
>
> ​	ξ∈(a,b)
>
> ​	f(ξ)=0

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211215181525477.png" alt="image-20211215181525477" style="zoom: 67%;" />

#### 1 罗尔定理 Rolle

> 1闭区间连续
>
> 2开区间可导
>
> 3f(a)=f(b)
>
> ​	则(a,b)至少存在一点ξ,使得 f'(ξ) = 0;



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211215180640776.png" alt="image-20211215180640776" style="zoom:50%;" />

几何意义: 2个函数端点值相等,则曲线中有一点必定与x平行



> Ex.1

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211215181137754.png" alt="image-20211215181137754" style="zoom:50%;" />



#### 2 拉格朗日定理 Lagrange

> [a,b]连续
>
> (a,b)可导
>
> ​	则存在 ξ∈(a,b), 
>
> ​			f'(ξ) =  [f(b)-f(a)] / (b-a)





几何意义: 对于y=f(x)这条曲线,有一个点的斜率与直线AB平行,就是斜率相等

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211215182731893.png" alt="image-20211215182731893" style="zoom:67%;" />

```
Ex2
```



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211215183221288.png" alt="image-20211215183221288" style="zoom:67%;" />



#### 3 柯西中值定理 Cauchy

> f(x),g(x) //g(x) != 0 
>
> ​	[a,b]连续
>
> ​	(a,b)可导
>
> 则存在ξ∈(a,b) 
>
> ​	f'(ξ)/g'(ξ) = [f(b)-f(a)] / [g(b)-g(a)] 



一般解法":

一般出小题,大题目前我也不会做(证明题)

```
已知函数f(x)=... ,在闭区间[a,b]满足 拉格朗日/罗尔定理则f'(ξ)中的ξ=____?
	两个定理形式都是f'(ξ)=...
	罗尔:
	
	
```

> 
>
> 罗尔:<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211219180751190.png" alt="image-20211219180751190" style="zoom:50%;" />
>
> 拉格朗日:
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211219203417228.png" alt="image-20211219203417228" style="zoom:50%;" />
>
> 总结一般解题步骤:
>
> ​	1 先求导
>
> ​	2 看两个定义
>
> ​	3 求出ξ



​	





### 二 洛必达法则

对于极限类型为0/0型,∞/∞型我们通常把这种极限叫做**未定式**.

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211215215345412.png" alt="image-20211215215345412" style="zoom:67%;" />

你给我钱我给你论文,洛必达从他的老师伯努利手里买了这篇论文并冠名自己的名字 L'Hospital. 他本人并不是数学家只是有钱罢辽.



>
>
>使用洛必达需要注意一些事项:
>
>​	可导和不为零以及洛完之后极限存在
>
>​	分母求导不能为0,每次使用完L之后判断可以是否继续使用L,洛必达配合等价使用
>
>​	洛必达之后某个极限不存在这个方法就失效了
>
>然后就直接 分子求导/分母求导



其他类型0*无穷, ∞-∞,0^0,1^∞等可以适当进行恒等变换再用洛必达



#### 0/0洛必达

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211216142442356.png" alt="image-20211216142442356" style="zoom:67%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211216142709775.png" alt="image-20211216142709775" style="zoom:67%;" />

#### 无穷/无穷



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211216142958866.png" alt="image-20211216142958866" style="zoom:67%;" />



![image-20211216143207968](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211216143207968.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211216143832342.png" alt="image-20211216143832342" style="zoom:67%;" />





#### 其他未定式

0*无穷, 无穷-无穷, 0^0, 1^无穷, 无穷^0

可以通过适当变形转换0/0,无穷/无穷再使用洛必达.



> 无穷-无穷<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211216145325971.png" alt="image-20211216145325971" style="zoom:67%;" />







> 1^无穷<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211216145847722.png" alt="image-20211216145847722" style="zoom: 50%;" />



> 0*无穷
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211216150126027.png" alt="image-20211216150126027" style="zoom:50%;" />



> 0^0



#### 一般步骤:

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211219204518700.png" alt="image-20211219204518700" style="zoom: 67%;" />



> ![image-20211219205528009](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211219205528009.png)
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211219205809770.png" alt="image-20211219205809770" style="zoom: 33%;" />
>
> 

> TODO
>
> 第一题可用泰勒-但是我还不会
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211219220317712.png" alt="image-20211219220317712" style="zoom: 50%;" /> 





## 5.0 导数应用



### 一 单调性与极值

第一判定,第二判定之间的区别是: 第一判定是根据驻点左右增减区间判断这个点是极大值极小值,并且可以知悉周围左右的单调性

第二判定只可以知道驻点,根据驻点二阶导数符号判断极大值还是极小值

#### 1. 判断单调性

如果f(x)在[a,b]连续, (a,b)可导 //闭区间上连续函数的性质. 闭区间连续开区间可导

>用导数符号判断单调性
>
>​	f'(x) > 0, 单调增
>
>​	f'(x) < 0, 单调减

**驻点** stationary point

>f'(x)=0,则成为函数驻点
>
>//不是所有驻点都是函数极值点,倒数不存在也可作分界点或极值点

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217193757805.png" alt="image-20211217193757805" style="zoom:67%;" />



**一般解题方法**

> 讨论单调性的一般方法
>
> 	1. 找出f(x)的Domain
> 	1. 利用f'(x)=0求出驻点
> 	1. 利用驻点划分区间,再分别讨论区间导数符号

​	

#### 2. 极值判定

```
极值是局部概念,代表了函数的凹凸性处的极高值极低值.
极值一定是{
	​	f'(x)=0的点(驻点)
	​	f'(x)不存在的点
}
```



>**第一判定**
>
>​	1 当x<x0时 f'(x)>0, 当x>x0时 f'(x)<0. 极大值的点 //图像先上升再下降
>
><img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217195442180.png" alt="image-20211217195442180" style="zoom:50%;" />
>
>​	2 当x < x0时,f'(x)<0.当x>x0时, f'(x) > 0. 极小值的点 //图像先下降再上升
>
><img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217200236356.png" alt="image-20211217200236356" style="zoom:50%;" />
>
>​	极值点就是单调区间的分界点,区分增区间与减区间



>第二判定
>
>​	f(x)具有二阶导数, f'(x)=0
>
>​	1 f''(x) > 0. 极小值
>
>​	<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217200659260.png" alt="image-20211217200659260" style="zoom:50%;" />
>
>​	2 f''(x) < 0. 极大值
>
>​	<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217204222921.png" alt="image-20211217204222921" style="zoom:50%;" />
>
>两种情况下不能使用第二判定:
>
>​	f'(x)不存在,f''(x)=0



> 求极值的一般方法
>
> 1 定义域
>
> 2 找出f'(x) = 0点作为驻点, 以及f'(x)不存在的点
>
> 3 根据分界点来求极值(用一二判定)
>
> ​	一: 列表出所有的分割区间,看3个相邻区间的中间区间的导数符号,是否与两边不一致,否则不是极值点
>
> ​	二:f''(驻点)判断符号是否大于0,是则极小值驻点. 小于零极大值驻点. 再把驻点带入f(驻点)得极值即可
>
> ​	
>
> 两个判定定理的区别:
>
> ​	定理一是用两侧符号来推测驻点是否为极值点, 增-驻-减是极大值,减-驻-增极小值.如果两侧单调相同则这个驻点无极值
>
> ​	定理二是用二阶导的符号来判断这个点是否为极值,二阶导大于0就是极小值,二阶导小于0就是极大值.再把驻点带入f(x)才能得出具体极值.定理二不能判断驻点左右的单调性.
>
> 



ex

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217211918791.png" alt="image-20211217211918791" style="zoom:67%;" />

### 二 最值

```
最值是一个全局概念,最值唯一但是最值点可以多个他们都是相同的.
闭区间: f(x)单调的话最值就是[a,b]
开区间: 如果只有一个极值点那么就是最值
```

> 一般步骤:
>
> ​	1 令f'(x)=0求出驻点,f'(x)不存在的点, 断点
>
> ​	2 计算驻点,导数不存在点,断点
>
> ​	3 比较得出最值, 最大值最小值



开区间:

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217212644555.png" alt="image-20211217212644555" style="zoom:67%;" />



闭区间:

​	<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217213432830.png" alt="image-20211217213432830" style="zoom:67%;" />



####  实际问题的最值

```
实际问题不可能取到端点,没有导数不存在的情况
	一般步骤为:
		1建立目标函数
		2求最值点,比较最值点
```

>Ex. 某商品成本Cost(x)=5x+200,收益R(x)=10x-0.01x^2,求每批生产多少个可以将利益最大化?
>
>​	<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217220617143.png" alt="image-20211217220617143" style="zoom:50%;" />



### 三 曲线的凹凸性与拐点

>判断曲线的凹凸看他的二阶导数
>
>​	f"(x)>0 他就是凹的 //极小值点
>
>​	f"(x)<0 他就是凸的 //就是极大值点
>
>​		//f'(x)判断单调性
>
>
>
>拐点是曲线凹与凸的分界点
>
>​	(x0,f(x0)) 为曲线y=f(x)的拐点
>
>​	拐点的二阶导=0,或者二阶导不存在

一般步骤:

1 确定f(x)的定义域

2 f'(x),f"(x), 找出f"(x)=0的点或是f"(x)不存在的点

3 以"步骤2"为分界点将定义域分割,在区间内讨论f"(x)的凹凸区间,判断分界点是否拐点.



> Ex
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217224005890.png" alt="image-20211217224005890" style="zoom:67%;" />
>
> 可知 
>
> ​	曲线的凹区间(-无穷,0)和(1,+无穷),凸区间(0,1)
>
> ​	拐点是(0,1)和(1,0)



```
给出一个函数 y=3x^4-4x^3+2求凹凸区间和拐点
	0确定函数定义域=R
	1求出y',y"
	2根据y"=0,找出驻点或导数不存在点
	3根据驻点将定义域划分区间
	4列表判断分割区间内凹凸性(二阶导数的符号f">0=凹,f"<0凸)
	5根据如果两侧曲线凹凸性相异,则该点为拐点(x,f(x))求出坐标.
```

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211220113759889.png" alt="image-20211220113759889" style="zoom:50%;" />







### 四 渐近线

1 水平渐近线

>lim f(x) = b, 直线y=b就是y=f(x)的水平渐近线
>
>x->∞
>
>//就是求x趋于∞的函数极限

>Ex. y=1/(x-1)的水平渐近线
>
>​	<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217224747270.png" alt="image-20211217224747270" style="zoom:33%;" />
>
>​	y=0这条直线就是他的水平渐近线



2垂直渐近线

```
求间断点,定义域边界,分母=0
```

> ![image-20211217225307759](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217225307759.png)
>
> 直线x=x0就是曲线y=f(x)的垂直渐近线

> Ex.
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217225525036.png" alt="image-20211217225525036" style="zoom:50%;" />
>
> 所以x=1,x=-1就是y=f(x)的垂直渐近线



例题

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217225850440.png" alt="image-20211217225850440" style="zoom:67%;" />

ex2

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211217230237160.png" alt="image-20211217230237160" style="zoom:50%;" />



2021年12月17日23:02:52

明天把红宝书的题做一下开始积分.
