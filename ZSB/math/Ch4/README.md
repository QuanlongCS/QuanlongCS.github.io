[toc]



# 常微分方程



> Ordinary differential equation

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113161953157.png" alt="image-20220113161953157" style="zoom:50%;" />

## 0. 基本概念



| 微分方程     | 必须含有y与y的微分(导数)             |                                                |
| ------------ | ------------------------------------ | ---------------------------------------------- |
| 阶           | 最高阶导数的阶数(求导的次数)         | n阶微分方程,n>=2称为高阶微分方程               |
| 线性微分方程 | 未知函数 全是一次幂, 忽略x           |                                                |
| 解           | 代入方程能成为恒等式                 |                                                |
| 通解         | 任意常数相互独立, 个数与方程的阶相同 |                                                |
| 初始条件     | 未知函数和导数在某个特定点的值       | y(0)=1, 意味x=0时y=1.  y'(0)=1, x=0时y的导数=1 |
| 特解         | 由初始条件而确定的不含任意常数的解   |                                                |

| C    | 相互独立的常数(不能合并) | 两边同时积分+C后可合并为一个C |
| ---- | ------------------------ | ----------------------------- |
|      |                          |                               |
|      |                          |                               |
|      |                          |                               |



> 
>
> 阶
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113161021048.png" alt="image-20220113161021048" style="zoom:50%;" />

> 线性微分方程
>
> 
>
> ![image-20220112113439056](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220112113439056.png)
>
> 
>
> ![image-20220112113500525](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220112113500525.png)

> 解 y=f(x)![image-20220113161359994](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113161359994.png)









## 1.1 一阶微分方程









### 可分离变量微分方程

先分离再积分



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220112114456423.png" alt="image-20220112114456423" style="zoom:67%;" />





<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220112114734746.png" alt="image-20220112114734746" style="zoom:50%;" />





> Ex.1
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220112115124986.png" alt="image-20220112115124986" style="zoom:67%;" />
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113162953980.png" alt="image-20220113162953980" style="zoom:50%;" />
>
> tips
>
> ​			导数此时可以看做微分与导数, 也就是y'视为dy/dx如此就可以分离开.
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220112115850891.png" alt="image-20220112115850891" style="zoom:67%;" />

关于c的问题,c代表任意独立的常数. 形式上C=C1=C2

下面这道题,c1代表着两边同时积分后的常数它们可以合并为一个常数.c2这个是e^c1是一个新的常数. c3是正负c2也是一个常数.

三个常数无法合并因此使用三个C来代表

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113213303602.png" style="zoom:67%;" />







### 齐次微分方程



含有未知数的地方都可以化为y/x的形式。

![image-20220114161606177](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220114161606177.png)

![image-20220114161744793](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220114161744793.png)



两边同时被求积分都是ln时c也加上ln便于计算





![image-20220114164758967](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220114164800304.png)





1 化为齐次微分的标准形式

2 u=y/x， y=ux即y'=(ux)' 代入齐次方程

3 化简再积分

4 回代u=y/x 得到通解

### ⭐⭐一阶线性微分方程





![image-20220113163447196](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113163447196.png)



> Tips:
>
> ​	对于齐次微分方程你可以选择用可分离变量来解,也可以选择用这个通解公式(这个公式就是由分离变量推导出的).
>
> ​	对于非齐次只能使用公式
>
> ​	非齐次方程的通解=齐次方程的通解+非齐次方程的特解.
>
> 



例题:

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113163647309.png" alt="image-20220113163647309" style="zoom:70%;" />





![image-20220114203446928](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220114203446928.png)

## 1.2可降阶的高阶微分方程

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113164206523.png" alt="image-20220113164206523" style="zoom: 67%;" />

### 1 n阶

对于n方程,它的的通解也应该有n个任意独立常数

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113215502872.png" alt="image-20220113215502872" style="zoom:67%;" />



### 2 不含y

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113215656434.png" alt="image-20220113215656434" style="zoom:67%;" />

换元之后还需要把它换回来,再求一次积分即可再加上一个C2. 要注意的是2阶只能有2个C.

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113220552590.png" alt="image-20220113220552590" style="zoom:67%;" />



### 3 不含x

//TODO 我不太理解y“的时候dp/dx 

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113220843458.png" alt="image-20220113220843458" style="zoom:67%;" />

![image-20220113225228508](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220113225228508.png)







## 2.1 ⭐⭐二阶 常系数 线性 微分方程

二阶线性齐次微分方程

二阶线性非齐次微分方程



标准形式是y"+py'+qy=f(x)

这里p,q都是常数,f(x)为已知项如果fx=0成为齐次微分方程,fx!=0非齐次微分方程



![image-20220114103032670](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220114103032670.png)

> 这句话意思: 非齐次方程通解=齐次方程通解+非齐次特解 
>
> //TODO 遗憾的是前面2个定理我不知道什么意思



### 齐次方程解法

![image-20220114104520417](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220114104520417.png)





特征根法: ![image-20220114104151086](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220114104151086.png)







### 非齐次方程解法

> y=Y+y* 就是非齐次方程通解

![image-20220114104419582](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220114104419582.png)

\





> 解释一下下面的表
>
> 0 非根0,单根1,重根2
>
> ​	x^0, x^1, x^2 乘在一般形式前面
>
> 
>
> 1 Pn(x)是多项式, Rn(x)是他的多项式一般形式.
>
> ​	Ex. 3x+1, R=Ax+B
>
> 
>
> 2 e^(ax)照抄就可以了











![image-20220114104442287](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220114104442287.png)



### 一般解法



1 f(x)=P(x)n次多项式

0次多项式就是非零常数,一般形式为A

1次多项式是x,一般形式Ax+B

![image-20220115202455052](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220115202455052.png)











<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220115203245387.png" alt="image-20220115203245387" style="zoom:33%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220115203418853.png" alt="image-20220115203418853" style="zoom:33%;" />











2 多项式乘e^ax

![image-20220115202954364](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220115202954364.png)

第三步求导的时候,只对x进行求导就行.里面的待定系数可以提出去,其他正常按照求导法则

如果有e^x(a+b)的利用导数乘法法则,a+b)'.e^x+e^x'(a+b)



3 三角函数乘e^ax

![image-20220115211936762](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220115211936762.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220115212335803.png" alt="image-20220115212335803" style="zoom:50%;" />

![image-20220115212420228](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220115212420228.png)



### 其他题型:

已知通解求微分方程.

```
1找出特征根
2写出特征方程
3写出对应微分方程
```

![image-20220115163042111](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220115163042111.png)	

