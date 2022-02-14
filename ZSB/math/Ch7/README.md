# 多元函数积分学



## 1.1二重积分

> 二重积分的几何含义: 曲顶柱体的体积

### 1.1.1二重积分的概念与几何意义



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212113338995.png" alt="image-20220212113338995" style="zoom:50%;" />

![image-20220212115058911](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212115058911.png)

面积元素可以视为分割后的每一块的小面积

积分区域D可以在坐标轴画出来围城图形

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212143902354.png" alt="image-20220212143902354" style="zoom:33%;" />

![image-20220212115437148](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212115437148.png)



```
Ex.
```

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212115714692.png" alt="image-20220212115714692" style="zoom: 50%;" />	其中z=f(x,y)可以视为他的高, D={x[0,1],y[0,1-x]; 就是二重积分基本形式



### 二重积分的性质

![image-20220212144451441](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212144451441.png)

![image-20220212144519997](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212144519997.png)





奇零, 偶倍

![image-20220212144837309](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212144837309.png)





### 二重积分的计算



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212165727647.png" alt="image-20220212165727647" style="zoom:67%;" />

Ex.

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212170226407.png" alt="image-20220212170226407" style="zoom:67%;" />



类似于求偏导, 求二重积分就是对dy求积分将x视为常数...

对于(x+y)dy这种的原函数=yx+1/2 y^2.<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212171011066.png" alt="image-20220212171011066" style="zoom:33%;" />



![image-20220212170808702](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212170808702.png)

#### 直角坐标计算



> 确定积分类型再计算二重积分
>
> 1画草图
>
> 2确定xy的范围
>
> 3求积分, 如果是x型就是∫dx∫dy
>
> 如果是y型就是∫dy∫dx
>
> ![image-20220212191948886](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212191948886.png)

![image-20220212181445044](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212181445044.png)

![image-20220212191103123](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212191103123.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212194011978.png" alt="image-20220212194011978" style="zoom:67%;" />



> 以上我们可以看出, 关于x型区域很好发现,y型需要辨别一下. 辨别方式就是画直线(横线, 看是否有边与它平行) 一般来说x轴不用看就知道是x轴,一般画竖线





#### 极坐标计算

![image-20220212194630581](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212194630581.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212195353726.png" alt="image-20220212195353726" style="zoom:67%;" />







![image-20220212195720010](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212195720010.png)



![image-20220212200407040](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212200407040.png)

![image-20220212200752120](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212200752120.png)





![image-20220212201031484](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212201031484.png)



![image-20220212201346831](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220212201346831.png)









#### 交换积分次序或改变积分形式

> 题目给出的积分是X型的现在需要你转换成Y型, 然后判断他的积分区间

![image-20220213100733661](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213100733661.png)





![image-20220213100948072](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213100948072.png)



![image-20220213104537593](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213104537593.png)

X型Y型的区别在于他们的积分区间顺序, 第一个积分区间是X的范围就是X型

![image-20220213111027140](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213111027140.png)

> 交换积分次序适用于非极坐标表示, 也就是如果遇到pi/2还是使用学习极坐标之前的表达. (sin函数图像里的值)

![image-20220213114725931](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213114725931.png)

积分形式

![image-20220213114816989](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213114816989.png)



![image-20220213115413152](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213115413152.png)



![image-20220213115732264](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213115732264.png)





### 二重积分的应用

![image-20220213143438823](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213143438823.png)

D表示一个底面积, f(x,y)表示高或者说表面surface

解决问题时找底和高. 

D: 关于Z=0的函数

z=f(x,y)的函数, z就代表高

![image-20220213144757894](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213144757894.png)



## 曲线积分



> （1）对[弧长](https://baike.baidu.com/item/弧长)的曲线积分 （第一类曲线积分）

>（2）对[坐标轴](https://baike.baidu.com/item/坐标轴)的曲线积分（第二类曲线积分）
>
>注意第二类的正负号

### 对弧长的曲线积分

> 弧长就是一条弧线, 类似于一个半圆的周长

![image-20220213150802966](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213150802966.png)



> 计算

![image-20220213152848549](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213152848549.png)



![image-20220213155529416](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213155529416.png)



![image-20220213160832071](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213160832071.png)



### 对坐标的曲线积分

与方向有关

![image-20220213170928188](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213170928188.png)

性质

![image-20220213171002892](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213171002892.png)

计算方法就是代入

![image-20220213171707666](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213171707666.png)



![image-20220213172822406](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213172822406.png)





## 格林公式⭐x5

> 如果时顺时针那就是负向, 结果加上负号即可
>
> dx对应部分时P, dy对应部分是Q
>
> 用公式的时候: 由xx公式可知

![image-20220213173957547](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213173957547.png)

xQc - Py交易	//(= ε =)这样就不会记混了

![image-20220213174221188](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213174221188.png)

⭐

![image-20220213174748553](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213174748553.png)



## 曲线积分与路径无关

> 充要条件<=>充分必要条件, 指的是a和b两个条件可以互相推导 

![image-20220213200158621](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213200158621.png)



![image-20220213200411183](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220213200411183.png)
