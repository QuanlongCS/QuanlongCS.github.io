# 第五章向量代数与空间解析几何

> 分为三个部分: 向量, 空间平面与直线
>
> ​	平面对应的是法向量(法线normal一般用向量n{A,B,C}来表示),
>
> ​	直线对应的是方向向量(s{n,m,p});把握好两个向量的位置关系这一部分是不难的.
>
> ​	空间曲面与曲线: //TODO



## 5.1 向量代数

### 0.1 空间直角坐标系.

对应表示坐标方式

x:(x,0,0)

y:(0,y,0)

z:(0,0,z)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122124951991.png" alt="image-20220122124951991" style="zoom:67%;" />

#### 空间之间2点距离(就是算向量的模,表示为距离也就是一个数)

![image-20220122130408866](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122130408866.png)





### 1.1 向量

a向量: 既有大小又有方向的量. 大小,方向相同的向量记作两向量相等

![image-20220122132427038](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122132427038.png)

**b**向量的模: 就是向量的大小

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122151448572.png" alt="image-20220122151448572" style="zoom:50%;" /> 也叫向量的**距离公式**



模为1的向量叫做单位向量, 模为0的向量叫做零向量





#### c 方向角与方向余弦

​	θ就是方向角, cosθ就是方向余弦.

向量/向量的模



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220118100703365.png" alt="image-20220118100703365" style="zoom:50%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122153024691.png" alt="image-20220122153024691" style="zoom:67%;" />

#### 单位向量

向量a平行的的单位向量= ± a/|**a**| //a的模

#### 投影



向量在坐标轴的投影 Projection n.投影

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122160455244.png" alt="image-20220122160455244" style="zoom:67%;" />

​	其中cos<a,b>代表ab之间的夹角.

![image-20220124143137547](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220124143137547.png)



### 1.2 向量的运算

0  三角形法则后**AB**+**BC**=**AC**

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122153958420.png" alt="image-20220122153958420" style="zoom:67%;" />

​	坐标下的表示为<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122154655993.png" alt="image-20220122154655993" style="zoom:50%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122154747979.png" alt="image-20220122154747979" style="zoom:50%;" />







1 线性运算(+-*/): 线性运算之后仍是向量的形式, 只将对应坐标进行线性运算即可



2 向量的数量积(点乘)

​	<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122155249710.png" alt="image-20220122155249710" style="zoom:50%;" />

Ex.<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122155334021.png" alt="image-20220122155334021" style="zoom: 33%;" />



3 向量积

|**a**||**b**|sinθ=|**C**|

|c|叫做a与b的向量积记作: <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122160933180.png" alt="image-20220122160933180" style="zoom:50%;" />这里是叉乘.

> 向量c垂直于向量ab所组成的平面.



表示为:

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122161728428.png" alt="image-20220122161728428" style="zoom: 50%;" />

其中行列式这里的计算规律为: i-j+k, 行列式内计算i 不看i所处的行和列(jk同), 3 交叉相乘再相减 4 去掉ijk得到的坐标就是向量c

Ex. ![image-20220122162029973](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122162029973.png)



> 正交:垂直
>
> 点乘的结果还是向量
>
> 叉乘的结果是一个新的垂直与ab的向量



#### 向量的夹角

![image-20220124161708371](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220124161708371.png)

点乘得出的是个数量,又叫数量积

叉乘的出的是法向量C,又叫向量积



## 5.2 空间平面与直线

```
这一小节主要在探究平面与直线的位置关系.
	n=法向量{ABC} 法线 normal vector
	而直线是方向向量 s={nmp}
```

### 1 空间平面方程

> 1 平面的点法式方程





​	由**平面**和垂直于平面的**法向量(**想想什么是法线)构成

​	向量Mo-M是平面的中的一条线,向量n是垂直于MM的法向量,那么向量n就垂直于MM也就是垂直于平面.



```
平面的方程是可推导的就是2个向量的数量积. 
	平面向量为一个起点x0题目会给出, 再假设一个终点x
	法向量为n[ABC]题目一般会给出
	两个向量做点乘结果使其为0.
	方程的形式就是：ABC.(x-x0,y-y0,z-z0)在化简 = A(x-x0)+B(y-y0)+C(z-z0)=0　
```



![image-20220122163637482](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122163637482.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122164232991.png" alt="image-20220122164232991" style="zoom:50%;" />



坐标表示为: **点法式方程一般形式**![image-20220122164613043](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122164613043.png)

一般题目: 已知起点M点, 法向量**n**. 求方程.

![image-20220122165302367](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122165302367.png) 



> 2 平面的一般式方程
>
> 一般题目是求 特殊位 平面用一般方程.
>
> ​		1假设特殊方程
>
> ​		2将M0点代入方程
>
> ​		3回代得出方程平面

点法式方程将ABC乘进去再写开, 再将D=-Ax0-By0-Cz0就得到一般方程

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122170345661.png" alt="image-20220122170345661" style="zoom:67%;" />

这里的D类似与截距或者高度, 平行于[],[]的系数就是0(ABC)

```
D=0时 Ax+Bx+Cz=0 平面通过原点
C=0,D!=0时, 对应的是z轴,平面平行于z轴但是D!=0,所以有一定的高度 Ax+By+D=0
C=D=0,平面经过z轴,且D的高度使0 Ax+By=0
B=C=0时, BC对应yz,没有x轴平面与yOz重合平行. Ax+D=0

```

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122171625380.png" alt="image-20220122171625380" style="zoom:67%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122171602206.png" alt="image-20220122171602206" style="zoom: 50%;" />



Ex.

经过z轴表示: Cz=0,D=0平面通过原点.

![image-20220122172107398](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122172107398.png)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122172959111.png" alt="image-20220122172959111" style="zoom:50%;" />

截距

![image-20220122172731597](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122172731597.png)





#### 2 总结 :两个平面位置关系

```
通过两个平面的法向量位置关系来判断2个平面的位置关系.
找出法向量
```

![image-20220122174307608](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122174307608.png)

> 两个平面位置关系:
>
> ​	1平行 n1//n2: 两个平面平行, 2平面的2个向量互相平行.
>
> ​		A1/A2=B1/B2=C1/C2 != D1/D2.(D不能相同否则重合了)
>
> ​	2垂直 n1⊥n2: 两个平面垂直那么平面的2个向量也互相垂直
>
> ​		n1.n2=0 //cos90°
>
> ​		A1A2+B1B2+C1C2=0
>
> ​	3相交/重合
>
> ​		相交: A1/A2=B1/B2=C1/C2 不成立
>
> ​		重合: D1/D2=A1/A2=B1/B2=C1/C2



Ex. 一般解题: 先找出2个平面的法向量n1,n2. 再对n1 n2进行点乘或者相除即可判断位置关系

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122174822829.png" alt="image-20220122174822829" style="zoom:67%;" />

平行重合意味着d1/d2也是要和前面部分比值一致的



> 平面夹角

```
平面夹角就是2平面法向量的夹角.你一定记得
```



定义平面为:

PI1: A1x+B1x+C1+D1=0 向量**n1**={A1,B1,C1}

PI1: A2x+B2x+C2+D2=0 向量**n2**={A2,B2,C2}

cosθ=(n1.n2)/(|**n1**||**n2**|)  //向量的数量积部分

![image-20220122203249339](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122203249339.png)

当平面垂直时夹角为pi/2, 两平面平行时夹角0





> 点到平面的距离



```
其中ABC是法向量N{A,B,C}
x0.y0.z0是已知点
```



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122203315741.png" alt="image-20220122203315741" style="zoom: 67%;" />





 Ex.![image-20220122203643232](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122203643232.png)







### 3 空间直线方程

```
题目给出已知点P[],需要我们自己去找出*方向向量*s{m,n,p},再把方程写出点向式
```



> 1直线的一般式 图5-7

![image-20220122204929383](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122204929383.png)

题目给出2个联立方程, 以及已知点M求直线方程:

S=n1 x n2 //叉乘 行列式,找出垂直向量

再写成点向式





<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122205432670.png" alt="image-20220122205432670" style="zoom:67%;" />



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122205726094.png" alt="image-20220122205726094" style="zoom:67%;" />







> 直线的标准式(点向) 图 5-8



![image-20220122204317124](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122204317124.png)

题目: 求过点M(1,1,0) 且垂直于平面PI: y+2z-2=0的直线方程

1.  找出n{ABC},从直线方程里找,没有x项意味着x为0
2. 将M起始点代入x-x0,y-y0,z-z0
3. 分别除以ABC





>直线的参数方程

将点向式推导,另每一个单独的式子=t,他们一定会得出同样的t,再把式子移到右边得出x的方程

![image-20220122210032289](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122210032289.png)

我们需要的还是s={m,n,p}

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122210541258.png" alt="image-20220122210541258" style="zoom:50%;" />

```
已知直线方程L的点向式,平面PI的方程求交点
	令直线方程L的每一项都=t.再移向{x=t,y=2t+1,z=3t+2}这种形式
	把xyz代入直线的方程得出t.
	回代到方程xyz关于t的方程{}
	得出焦点坐标.
```





> 直线的两点式方程

```
先用一点做假设点M1,再根据这两点本身就是一个方向向量得出点向式方程
```



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122210924614.png" alt="image-20220122210924614" style="zoom:67%;" />





<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122211018348.png" alt="image-20220122211018348" style="zoom:50%;" />

#### 4 总结: 两条直线的位置关系

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122211229930.png" alt="image-20220122211229930" style="zoom: 67%;" />



利用2个方向向量来判断2条直线的关系. 

​	如果向量相除成比例,那么就是平行

​	如果向量点乘为0那么就是垂直.   //向量a.向量b=0   //cos Pi/2=0 

完全是根据第一节里向量的点乘运算. (点乘是相乘再相加,而向量的三角形法则尾-首得出向量,平方后再开根号是距离)





### 5 ⭐直线与平面的位置关系

判断平面我们使用的是法向量(与平面垂直的向量), 判断直线使用的是方向向量(与直线同方向的向量)

n={A,B,C}; s=[m,n,p]



> 如果直线L与平面PI垂直,那么 直线就和平面的法向量是平行的. //在一个平面上放两只笔试一下.
>
> ​	<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122211958633.png" alt="image-20220122211958633" style="zoom:70%;" />



> 如果直线L与平面PI是平行的, 那么直线L就和我的平面的法向量是垂直的.
>
> ​	s.n //点乘=0
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122212226232.png" alt="image-20220122212226232" style="zoom:67%;" />

这里通常会判断直线与平面是否重合:

将直线一点代入平面方程,若成立则直线在平面上,否则为平行



> 求夹角使用的是正弦值sinθ=|s.n|/|**s**||**n**|



```
总结一下: 
	平面方程一般用的点法式,法向量在系数位置 n= A B C
	直线方程一般用的点向式,方向向量在分母   S= n m p
 	
```

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220122213129958.png" alt="image-20220122213129958" style="zoom:67%;" />



s⊥n时只需要再直线l上任意找一点P, P的坐标满足PI的方程则直线就在平面内.否则平行







## 5.3 ⭐空间曲面与曲线

//TODO 这一小节很迷惑,视频讲的也不清楚.先放着下面的笔记不具备参考价值.



![](https://gitee.com/quanlongcs/pic-bed/raw/master/img/20220123180303.png)

```
牢记简单的二次曲面方程 *特征* 及 *图形*
考题常以选择,填空小题出现.
```



### 1空间曲面及其方程

#### 旋转曲面

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220124122833782.png" alt="image-20220124122833782" style="zoom:67%;" />

有规律,yoz平面上曲线关于哪个轴旋转,哪个轴保持不动,另一个轴加上x. //模长

![image-20220124123240451](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220124123240451.png)





### 2简单的二次曲面

> 球面

大家都见过球的样子(虽不太符合精准定义),我就不画了

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123111630179.png" alt="image-20220123111630179" style="zoom:50%;" />

标准方程拆开后, x^2-2x.x0+x0^2 ...将每一项都拆开得到方程的一般方程:

​	x^2+y^2+z^2  + Dx+Ey+Fz//-2x那部分// + G//x0^2... 和R^2是常数//

​	1 				2						3

```
一些题目中会让求出一般方程的球心坐标和半径:
	可以使用配方法将其配成标准形式即可 (2次项系数的一半的平方,配成完全平方公式的形式(a+b)^2=a^+2ab+b^2)
	或者使用公式法: 坐标O( , , ) 半径R().
```

![image-20220123112921981](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123112921981.png)

Ex.  配方也是可以的,但是在不熟练的情况下会出错

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123114949969.png" alt="image-20220123114949969" style="zoom:67%;" />







> 2 柱面 (二元方程)

柱是由圆按着z轴上下平移得到的

方程特点:

```
二元方程. 
	2x^2-y^2=1表示的曲面是(双曲柱面)  //只含有2个独立未知数柱面方程
	例如x^2+y^2-2x=0也是含有x,y二元方程,所以为柱面
```



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123144114304.png" alt="image-20220123144114304" style="zoom:67%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123153850783.png" alt="image-20220123153850783" style="zoom:67%;" />





> 3 椭球面

```
abc代表在xyz轴上的高度
```



![image-20220123154850118](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123154850118.png)





> 4 旋转曲面

平面内一条曲线绕坐标轴旋转一周形成的曲面

```
特点: 
	1 其中两项次数一样,系数一样
	//y^2+z^2=x
	//x^2+y^2=z
2 旋转谁,谁不变,另外两项变成系数相同的二次项 
	
	
```

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123152647584.png" alt="image-20220123152647584" style="zoom:67%;" />







> 5 锥面

当z=z0时 把第三项移到右边,截面为椭圆.

同样的方法用到第一二项可以得到双曲线

![image-20220123161052608](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123161052608.png)

> 6 单叶双曲面

```
双叶双曲面的话等式右边=-1
```



![image-20220123161514357](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123161514357.png)

![image-20220123161726518](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123161726518.png)

> 7 椭圆抛物线
>
> 



![image-20220123161852191](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123161852191.png)

### 3空间曲线及其方程

 1方程:

题目给出一组方程, 将方程代入再判断类型



2 投影

```
若要求母线平行于哪个轴,就消去哪个轴变量
```



关于哪个坐标轴的投影柱面就消去其他的变量

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123170121662.png" alt="image-20220123170121662" style="zoom:50%;" />

消去的方式是让两个方程进行+-



> 求空间曲线坐标再平面的投影曲线	

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220123170512738.png" alt="image-20220123170512738" style="zoom:67%;" />
