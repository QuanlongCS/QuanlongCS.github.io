> Infinite series

# 第八章 无穷级数

## 8.1 常数项级数的概念及性质

### 数列

> 什么是数列?
>
> 数列分为 **等差数列** 与 **等比数列**. 
>
> ![image-20220216195016828](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216195016828.png)
>
> 等差数列有一个公差, 等比数列有公比. 前一项与后一项之间存在的关系就是这个公差与公比
>
> ![image-20220216195355010](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216195355010.png)



无穷级数与数列之间有什么关系呢?

> 数列只是简单的排列出来, 但是无穷级数是无穷多个数列的项进行相加![image-20220216202109871](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216202109871.png)

被放到的大M读作xigema ∑表示从 i=1的项一直**累加+=** 到无穷项. 计算机系的同学应该可以理解这点.



### 部分和

因为无穷级数是无穷的我们只能一窥它的部分和来推导整体的情况

前面部分使用部分和Sn的极限来判断这个级数是否有极限从而是否收敛.

![image-20220216202452465](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216202452465.png)

### 收敛与发散

![image-20220216210420146](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216210420146.png)



通过求级数部分和的极限判断级数是否收敛, 否则级数发散

![image-20220216205007859](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216205007859.png)

做题步骤:

```
1 求得Sn 部分和
2 求得Sn的极限值
3 即可判断收敛与否
```

### ⭐等比级数 与 调和级数

> 调和级数(Harmonic series)与音乐理论有一些联系

![image-20220216205341037](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216205341037.png)



### 无穷级数的基本性质

```
含有发散的运算基本都是发散的.
```

![image-20220216205850112](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216205850112.png)

![image-20220216210702753](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216210702753.png)



### 必要条件

如果级数收敛则通项极限=0

![image-20220216210810090](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216210810090.png)

反过来说: 如果通项极限!=0, 这个级数就是发散的

![image-20220216211025001](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216211025001.png)



## 8.2 正项级数与收敛法

什么是正向级数? 级数中的每一项Un都大于0

> **正项级数收敛的充分必要条件是部分和Sn 有界**



### ⭐P-级数

> 三大级数之一

观察P的值判断级数的收敛于发散

![image-20220216211633478](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216211633478.png)

如果是对数形式只看对数的指数

![image-20220216211833740](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216211833740.png)

![image-20220216211916080](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216211916080.png)

![image-20220216212005645](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216212005645.png)



### 比较审敛法(不等式/极限形式)

> 利用已知级数进行比较

大的收敛 => 小的也收敛

小的发散 => 大的也发散



![image-20220216212156775](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216212156775.png)

比较审敛法适用于正项级数, AB选项不能确定是正数 

![image-20220216212922067](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216212922067.png)

![image-20220216213451240](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216213451240.png)

<hr>



极限形式比较审敛法基本属于不等式的一个推导, 根据A的值判断之间的关系

![image-20220216213840547](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216213840547.png)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216214126910.png" alt="image-20220216214126910" style="zoom:67%;" />

计算可以使用等价代换

![](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216214244351.png)



### 比值审敛法(后项比前项)

![image-20220216214459199](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216214459199.png)

因为这些不是等比级数或者调和级数不能使用已知级数进行对比

上面的结论中p的比值<1代表说级数越来越小 直到收敛至某个数

大于1发散, =1不确定

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216214736698.png" alt="image-20220216214736698" style="zoom:67%;" />



### 根值审敛法

直接适用有n次方的级数, 将次方消掉. 然后同样的得出ρ值/rou/. <1代表正在逐渐收敛

大于1发散, =1不确定

![image-20220216214957062](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216214957062.png)

![image-20220216215708975](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220216215708975.png)





## 8.3 交错级数及其审敛法

### ⭐莱布尼茨判别法



形如![image-20220217101404882](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220217101404882.png)n的奇偶不同, 结果一正一负

> 正负项交替出现的级数

判别方法: 莱布尼兹	定理满足2个条件

计算的时候不用计算 -1^n 只是用来判别的一个条件

![image-20220217101849124](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220217101849124.png)



![image-20220217102018141](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220217102018141.png)



<hr>



### 绝对/条件收敛  (任意项级数)

> 绝对值收敛: 加绝对值=收敛
>
> 条件收敛: 加绝对值=发散, 不加确实收敛的

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220217102847972.png" alt="image-20220217102847972" style="zoom:67%;" />



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220217103215030.png" alt="image-20220217103215030" style="zoom:67%;" />

### ⭐交错P级数的结论



![image-20220217103242376](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220217103242376.png)





## 幂级数

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219143023956.png" alt="image-20220219143023956" style="zoom: 80%;" />

形如An x^n, 当x-x0=x就是x的幂级数



### 阿贝尔定理(收敛区间)

![image-20220219143315778](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219143315778.png)

![image-20220219143343030](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219143343030.png)

如果幂级数在x1处收敛则在(-x1,x1)处任意一点绝对收敛

如果幂级数在x2处发散则在(-∞,-x2)∪(x2,+∞)任意点发散

![image-20220219143637914](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219143637914.png)

推广

![image-20220219143856012](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219143856012.png)

将x^n推广之后会变成(x-x0)^n这表示以x0为中心距离为|x-x0|, 也就是<x1到x0点的范围距离



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219145218486.png" alt="image-20220219145218486" style="zoom:67%;" />

x-x0, x0=2

-2处收敛距离2为4个距离, 以2为中点向有走四个距离为6.

4<6所以是绝对收敛

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219145509108.png" alt="image-20220219145509108" style="zoom:67%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219145839076.png" alt="image-20220219145839076" style="zoom:67%;" />



### 收敛半径 收敛区间 收敛域

![image-20220219150112364](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219150112364.png)

![image-20220219150329228](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219150329228.png)对于R,-R点需要进一步进行判断

![image-20220219150534422](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219150534422.png) 





收敛半径



![image-20220219150913191](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219150913191.png)x=0处

1 求出ρ的值=limt|An+1/An|

2 R=1/ρ得到收敛半径R

3 收敛区间即为(-R,R)



![image-20220219151236093](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219151236093.png)这道题x-x0=x-(-1), 即以-1为中点.

半径为R的收敛区间



> 收敛域= 端点是否属于开闭区间, 收敛=闭区间, 发散=开区间

![image-20220219151801568](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219151801568.png)

求出收敛区间后 第二步x=-1,x=1代入进去原级数里分别判断端点的收敛性



### 和函数

S(x), 和函数可以逐项求导,可以逐项积分

![image-20220219162326902](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219162326902.png)

一般情况下只会遇到x^n幂函数这种函数， 所以尝试求导或者积分一定可以的

![image-20220219165043107](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219165043107.png)





![image-20220219165802843](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219165802843.png)

技术总结

1 收敛区域 （Sx）只能存在于连续的收敛域

​	a. 求出ρ值,R=1/ρ, 得到收敛区间(-R,R),根据-R和R判断收敛域

2 求和函数S(x), 观察用导数或者积分将Ax部分消掉, 等比函数求和公式, 再用积分或者导数

3 和函数=    , x∈

![image-20220219170253217](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219170253217.png)

x的次数不一致需要化成x*x^n, 最后再带回去![image-20220219170757682](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219170757682.png)





这一个是先积分的题目![image-20220219170929562](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219170929562.png)

![image-20220219170950326](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219170950326.png)

注意: 无论是先积分或是先求导, 在中间都要求再求和的. 公式就是等比级数求和a/1-q. 其他形式也遇不到



### 麦克劳林级数



![image-20220219173313147](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219173313147.png)



![image-20220219173529375](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219173529375.png)n的起点都是0



两种考查形式: 

从右往左, 求幂级数的和函数

![image-20220219175041167](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219175041167.png)

从左往右, 给定函数,让展开成级数的形式

![image-20220219175308801](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220219175308801.png)
