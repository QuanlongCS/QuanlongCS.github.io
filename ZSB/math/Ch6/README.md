[toc]

//TODO 

// 条件极值-拉格朗日乘数法



# 二元函数微分

一元函数: y=f(x)

二元函数: z=f(x,y)



## 概念

> 考点多是 二元函数概念,求极限,函数表达式,定义域

### 定义域

二元函数的定义域, 自变量x y两个的定义域范围. (答案写作集合的形式)

![image-20220202103017366](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220202103017366.png)

### 表达式

> 1.由简单表达式到复杂表达式-直接代入

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220202103306861.png" alt="image-20220202103306861" style="zoom:50%;" />



> 2由复杂到简单-恒等变形(凑)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220202111410400.png" alt="image-20220202111410400" style="zoom:67%;" />



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220202225309660.png" alt="image-20220202225309660" style="zoom:67%;" />

> 这个方法貌似可行



### 极限定义

![image-20220202111603125](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220202111603125.png)两种书写方式表达一致.



> 判断极限存在

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220202112001626.png" alt="image-20220202112001626" style="zoom:67%;" />

### 求极限

> 无法使用洛必达,其余与一元函数大致类似
>
> 



//TODO 二元函数求极限基本与一元函数求极限一致,所以需详细整理求极限的方法.

0. 对于极限代入结果存在的情况下都可以直接带入试一试.

1. 零x有界

![image-20220202112313382](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220202112313382.png)

1. 无穷小等价代换

   ![image-20220202112508222](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220202112508222.png)

2. 重要极限

1. 根号的情况: (1+X)^1/2 - 1 = 1/2x; 有理化: 分子分母都乘以根号的**共轭表达式**.

### 连续性

> 而考查一般也都是分段函数.初等函数在其定义域都是连续的,极限值就等于函数值
>
> //初等函数: 幂指对三角反三角,经过有有限次的四则运算

极限存在(函数值=极限值)<==>连续

![image-20220202114052572](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220202114052572.png)



![image-20220202114643890](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220202114643890.png)





## 偏导数与全微分

> 用定义求偏导数. (类似于导数定义求导数)
>
> 用公式求偏导数. (求y的偏导就把另一个x视为常数)

### 偏导数的概念与求导法则

一元函数导数的概念

![image-20220203100325687](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203100325687.png)

二元函数的导数叫做 偏导数. //实际求导过程中把另一个未知数视为常数,实则还是一元求导

![image-20220203101539755](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203101539755.png)

定义式求偏导方法:

![image-20220203101801991](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203101801991.png)

同理可得

![image-20220203103603697](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203103603697.png)



> 题目说对函数z=f(x,y)在(x0,y0)处的偏导数, 包含是z对x的偏导与z对y的偏导 //对y偏导时讲x保持不动,对自变量y进行加减计算
>
> 题目不说明具体对谁求偏导的话都是要算对x,y求偏导.



Ex.

![image-20220203103458398](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203103458398.png)



![image-20220203103701376](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203103701376.png)

x的部分进行了加减所以是对x进行求偏导,h-(-h) / h=2所以系数k=2



> 求偏导法

![image-20220203104045225](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203104045225.png)



![image-20220203104304414](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203104304414.png)

对于复合函数求导只需要利用一元函数<洋葱法则> 再进行求偏导就可以了



![image-20220203104432010](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203104432010.png)

对x求偏导就在式子里找到关于x的项, 只含y项视为常数求导为0. 若是xy结合项则是y视为系数

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203104815556.png" alt="image-20220203104815556" style="zoom:67%;" />

已知点求偏导,对常数部分直接带入,再求偏导

![image-20220203105306805](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203105306805.png)

对于x偏导,先将y代入

![image-20220203105540004](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203105540004.png)



![image-20220203110102408](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203110102408.png)



### 几何意义

![image-20220203110530743](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203110530743.png)

### 2 高阶偏导数

![image-20220203110757628](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203110757628.png)

对x求了一阶偏导之后再对x求一次偏导就是二阶偏导

对y求了一阶偏导之后再对y求一次偏导就是二阶偏导

![image-20220203111704147](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203111704147.png)

对x求了一阶偏导之后再对y求一次偏导就是二阶混合偏导

对x求了一阶偏导之后再对y求一次偏导就是二阶混合偏导

后混合偏导的结果时一致所以不需要算2次





### 3 全微分

全微分会和隐函数一起考察

![image-20220203142919347](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203142919347.png)

![image-20220203143115850](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203143115850.png)

对于特定点的全微分, 先求偏导再代入

![image-20220203143357392](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203143357392.png)



对于偏导,与正常求导的差别不大只不过在对于x和y时把其中一个进行求导另一个视为常数.

```
ln(x+y)'x = 1/x+y //隐含了一些东西. 复合函数求导 1/u. u=(x+y)再对u进行x求导相乘= x'=1,y'=0常数. 所以 ln(x+y)'x =1/x+y
```







#### 4 性质关系

![image-20220207161920569](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220207161920569.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/20220203144434.png" style="zoom:67%;" />





### 4 复合函数偏导数与全微分

链式法则看起来挺麻烦的, 类似于一元函数复合求导法所以直接使用洋葱法则

> 一般考点: 多元抽象符合函数的偏导数

直接带入法

![image-20220203155348220](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203155348220.png)



![image-20220205211002496](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220205211002496.png)













### 5隐函数的偏导数

>先对二元函数进行求偏导,2个所求偏导相除,前面加上符号
>
>



![image-20220203163416944](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203163416944.png)

![image-20220203163846808](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203163846808.png)

对y求偏导/对z求偏导, 前面加上负号.



![image-20220203164305159](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203164305159.png)







<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203164620892.png" alt="image-20220203164620892" style="zoom:67%;" />



先求偏导再代入, 如果遇到未知数则回到原题目方程去找.

![image-20220203164926991](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203164926991.png)



![image-20220203165842029](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220203165842029.png)



![image-20220205215708398](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220205215708398.png)



## 方向导数与梯度

### 方向导数

![image-20220204111902915](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204111902915.png)



方向导数= 方向余弦 x 偏导数

```
1 求函数的偏导
2 找出向量L=(终点-起点) 向量/模=方向余弦cosθ
3 方向导数 = 各个坐标轴的"方向导数"x方向余弦 再相加
	结果得出一个常数
```



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204112312222.png" alt="image-20220204112312222" style="zoom:50%;" />



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204112428927.png" alt="image-20220204112428927" style="zoom:50%;" />







### 梯度

grad: gradient,也可写成倒三角符号



```
1 求出函数偏导值
2 写成向量的形式. (类似于向量积行列式那里的ijk)

```



![image-20220204112620461](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204112620461.png)

![image-20220204112949794](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204112949794.png)



![image-20220204112933243](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204112933243.png)







### 最大值最小值

梯度的模

![image-20220204113151798](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204113151798.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204113233856.png" alt="image-20220204113233856" style="zoom:67%;" />



## 几何应用





### 切线与法平面



![image-20220204160811056](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204160811056.png)

```
1 用参数方程,切点坐标得到一个T值
2 对每个求导求导得到 切线 //也就斜率
3 写出切线方程与法平面方程
```

![image-20220204164052856](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204164052856.png)







<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204164208654.png" alt="image-20220204164208654" style="zoom: 50%;" />

![image-20220204164314726](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204164314726.png)







### 切平面和法线(法向量)

平面还是用点法式, 直线用点向式

![image-20220204164614561](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204164614561.png)



![image-20220204164646626](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204164646626.png)











![image-20220204165109790](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220204165109790.png)



























## 极值及应用

```
判别式进行判断后,如果时极值那就把点代入到原方程去.求的极值
```



### 非条件极值



必要条件

![image-20220205172238306](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220205172238306.png)

```都
二元函数z=f(x,y)在点(x0,y0)取得极值
	二元函数的一阶xy偏导存在
	且都=0  //驻点,但不一定是极值点
```

充分条件
![image-20220205172623471](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220205172623471.png)

```
二阶偏导的时候F''xy为B, 其中任意一个二阶偏导为带有平方的就说明有2点需要进一步用判别式分别讨论
```



![image-20220205180113002](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220205180113002.png)



> 其中 关于实际问题求最值
>
> ​	1建立目标函数
>
> ​	2求驻点
>
> ​	//驻点唯一且实际问题最值一定存在. 即



### 条件极值

![image-20220206142936911](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220206142936911.png)



```
长方体体积=长x宽x高
长方体面积=(ab+cb+ca)
```

![image-20220206144225764](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220206144225764.png)![image-20220206144753714](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220206144753714.png)
