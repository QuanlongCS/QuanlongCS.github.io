```
todo:
	不定积分-1臭微分2换元3分部积分4有理函数的不定积分
	
	周一之前把不定积分整理然后做宋浩的题,然后补充笔记,然后定积分
	有理函数的不定积分计算 2021年12月30日20:43:21 已完成
	微积分三大基本计算方法-极限 求导 积分这里的不定积分 定积分要多做题目来熟悉运算方法,达到与前两种一样的水平.
	
```

# 不定积分

![image-20211231142958234](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231142958234.png)

## 原函数,不定积分的概念与性质

> F(x)是原函数,F(x)求导之后得到导函数f(x)
>
> ∫f(x)=F(x)+C 其中C是常数Const,对导函数求积分就是得到原函数

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231143701800.png" alt="image-20211231143701800" style="zoom:50%;" />



积分与求导就是互逆运算. 相当于物质与反物质的关系(?)函数与反函数?

求一个函数的积分就是找出哪一个函数求导之后得到这个函数.

f(x)存在一个原函数,就存在无数个原函数,所+C就可以得到全体原函数.



> 不定积分:
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231144412485.png" alt="image-20211231144412485" style="zoom:50%;" />
>
> ∫ 提示这是一道积分题,
>
> f(x)dx把它看做一个整体可拆分形式,其中变量x部分是保持一致的
>
> 还要在复习一下微分,在凑微分会有用处.





```
求不定积分就是求导逆运算
求不定积分就是寻找一个原函数的过程
```

> 性质:
>
> 
>
> 1<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231145048341.png" alt="image-20211231145048341" style="zoom:50%;" />是
>
> 2常数可以随意提出来
>
> ∫k f(x)dx=k∫. 这个点很重要以后会经常使用
>
> 3和差性质
>
> ∫（fx+gx）dx=∫fx+∫dx



## ⭐基本积分公式

积分基本公式就像求导基本公式一样重要,某种角度也就是求导公式.你需要做的是把每一条求导公式默写再写出他的积分公式



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231145645606.png" alt="image-20211231145645606" style="zoom:67%;" />





下面是一下便于记忆的点

幂指



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231150326830.png" alt="image-20211231150326830" style="zoom:33%;" />



三角函数

![image-20211231150607423](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231150607423.png)





反三角

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231151046179.png" alt="image-20211231151046179" style="zoom:50%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231151210747.png" alt="image-20211231151210747" style="zoom:50%;" />







俩个不好记的,但是同样有规可循



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231151609148.png" alt="image-20211231151609148" style="zoom:50%;" />



> 由基本公式的推导得出较为复杂但是很有用的公式,推导过于复杂我也不是很会就不推了.往下凑微分里面会有.
>
> 在做题中体会常用加以简单记忆即可.

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231151956386.png" alt="image-20211231151956386" style="zoom:67%;" />



三角的一些基本公式二倍角,降幂,sin^2+cos^2=1等基础公式看整理的三角函数(可能还没发布出去)

三角函数网上有些讲师会有什么八卦图的方法,我的建议是不要看作用不大 三角函数主要是就sin=对/斜边,

sin^2+cos^2=1就这两个公式的推导,自己推导再就能很好的记忆而不是画个图形.





### 利用基本公式做题:

同济的例题很不错

> 检验积分结果的正确与否,就是对结果求导数

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231155919179.png" alt="image-20211231155919179" style="zoom:50%;" />







<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231160059708.png" alt="image-20211231160059708" style="zoom:50%;" />

这里笔误了下,降幂后直接求就好了,只是说在基本积分表中没有的三角函数可以用三角恒等式进行变换



## 解不定积分的方法



### 1 臭(凑)微分

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231163012514.png" alt="image-20211231163012514" style="zoom:67%;" />



只看这个应该很难理解清楚,但是你知道了这个再去看其他老师讲得凑微分你就可以很清楚了.

还有一点从外拿到里凑是求原函数,把他拿出来是求导.这是贯穿凑微分思想的中心. 凑表示配凑.微分,就是之前学的微分dy=y'dx那里.知道了这个你就不用再去重新复习微分了.



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231163939408.png" alt="image-20211231163939408" style="zoom:50%;" />



![image-20211231164504193](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231164504193.png)

河南专升本红皮书p108这道题得出的结论可以当公式用,非常重要.也就是上面基本公式我没有写出证明的原因,书上有证明不过很略.



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231165138764.png" alt="image-20211231165138764" style="zoom:50%;" />



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231165111889.png" alt="image-20211231165111889" style="zoom: 67%;" />



![image-20211231165443220](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231165443220.png)

### 2换元法

> 第二换元法分为几种情况

#### a.简单根式

只含有 一个根式n^√ax+b，直接进行换元令其 = t。

![image-20211231171605642](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231171605642.png)



#### b.含有2个根式

换元为2个根式的最小公倍数根

![image-20211231204616581](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231204616581.png)



#### //TODO 含有根式√(a^2-x^2) 或者√(x^2+-a^2)



使用三角代换



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231205206200.png" alt="image-20211231205206200" style="zoom:67%;" />

![image-20211231205836612](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231205836612.png)

![](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231205850744.png)



### 3分部积分

分部积分只需按照一个公式

![image-20211231205509524](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231205509524.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231210537245.png" alt="image-20211231210537245" style="zoom:50%;" />

你可能注意到前面的基本上公式和推导公式都没有∫lnx,现在有了可以当做结论.



还有在进行分布积分的运算时往后拿的顺序有区别的

> e^x> sin cos > a^x >lnx



![image-20211231211422474](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231211422474.png)



![image-20211231211948917](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231211948917.png)



还有一种情况是循环,∫abc= -(abc) + xxx 这时候把abc移到左边即可一般情况下会是一个负的表达式挪到左边就是2*表达式,再给右边/2即可. 也有其他情况但是如果挪过去抵消了那一定是你算错了.

> 什么时候是球原函数,什么时候只是简单的替换?
>
> 第一步是对函数进行分析,按照前面讲过分部积分顺序e^x总是优先.往后求原函数拿过去
>
> 第二部就是正常的按照分部积分的公式,uv-∫vdu

### 4简单有理函数的不定积分

有理函数会出现两种情况的分式多项式, 一种类似于分子<分母的情况成为真分式, 一种分子多项式大于等于分母的多项式成为假分式(一般通过配凑的分式转为C+1/x的形式在进行积分,以及拆项. 不动分母,让分子凑成分母的形式目的是消消乐)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231162817919.png" alt="image-20211231162817919" style="zoom:50%;" />

> [【合集】【心一学长】40分钟彻底搞懂有理函数不定积分所有类型与方法！_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1B7411X7uH)
>
> 这个视频对有理函数进行了总结,其中有多种方法可以使用方程,留数法. 选择喜欢的即可

#### 1 单因式

![image-20211230204854560](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211230204854560.png)

类似于下面这个, 就可以简单粗暴的分成3项

​	<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211230204935284.png" alt="image-20211230204935284" style="zoom:50%;" />



```
Ex. 1
	1. 因式分解,再拆项,得出等式
	2. 左右两边乘以公分母消项
	3. 比较同次项系数
	3. 求积分
```

![image-20211230205233169](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211230205233169.png)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211230210743457.png" alt="image-20211230210743457" style="zoom:67%;" />



#### 2 重因式

∫A/ (x-a)^n dx

![image-20211231134314355](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231134314355.png)

```
例题:
```

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231140043796.png" alt="image-20211231140043796" style="zoom:67%;" />

#### 3 质因式





![image-20211231140438425](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231140438425.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20211231141426279.png" alt="image-20211231141426279" style="zoom:50%;" />



> 书上这里还有俩关于三角函数结论,利用前面所学知识就可以解决. 
>
> 其中次数都比较高的用 奇拆偶降或是换元



2021年12月31日21:25:30写到这里时今天是2021的最后一天,如果你能看到这里祝你新年快乐.







# 定积分



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108202141876.png" alt="image-20220108202141876" style="zoom:50%;" />







## 一 定积分的概念

![image-20220105110911511](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105110911511.png)



与不定积分类似,只是增加了确定的上下限. 或者说根本没有不定积分,不定 indefinite.

增加了上下限[a,b]就确定了积分区间.

定积分表示的一个和式的极限.

### 2 几何意义



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105111249765.png" alt="image-20220105111249765" style="zoom:67%;" />



y=f(x)一条曲线与 x_0=a, x_1=b, y=0四条边围成的曲边矩形,定积分求的就是他的面积.

矩形的面积=底*高, [a,b]就是底, y=f(x)就是高.



![image-20220105112956410](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105112956410.png)

对于几何意义,其实就是底乘高,这个高是fx,底就是积分区间

### 3 存在定理

连续=积分存在(可积,可以求面积)

![image-20220105113322023](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105113322023.png)

有限间断点=积分存在(可积)





## 二 定积分的性质





![](https://gitee.com/quanlongcs/pic-bed/raw/master/img/20220105153516.png)



> ⭐偶倍奇零:
>
> <img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105155247027.png" alt="image-20220105155247027" style="zoom:50%;" />



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105155657421.png" alt="image-20220105155657421" style="zoom:50%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105155729305.png" alt="image-20220105155729305" style="zoom:50%;" />





## 三 定积分的计算

### 积分上限的函数及其导数

> 结论: 连续函数fx取变上限积分的定积分然后求导结果还是fx本身

![image-20220105172556614](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105172556614.png)

如果上下限颠倒的话就把他颠倒过来,加上符号(性质2:积分上下限改变,改变符号.)



如果是复合函数: ![image-20220105173228337](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105173228337.png)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105180121813.png" alt="image-20220105180121813" style="zoom:25%;" />



![image-20220105180630522](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105180630522.png)

这道题题目并没有说对它求导,但是我们可以主动求导

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105180727250.png" alt="image-20220105180727250" style="zoom:33%;" />



还能搭配洛必达食用

![image-20220105181243895](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105181243895.png)

### 牛顿-莱布尼茨公式(Newton-Leibniz)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105181645894.png" alt="image-20220105181645894" style="zoom:50%;" />

其实就没有不定积分,我从普林斯顿微积分里也没有找到不定积分,听某个专升本讲课老实说是为了降低难度. 这里定积分的计算直接求原函数,再带入上下限即可(牛顿莱布尼兹)

> 使用newton-Leibniz 需要注意被积函数需要在[a,b]区间连续, 举个栗子比如说1/x在[-1,1不连续也就不能利用N-L公式计算.] //这里就引申到了广义积分



```
总结一下就是: 如果积分区间含有x的话就是用积分上限函数求导,否则就用莱布尼兹.
```



### 3换元 //TODO



> 与不定积分类似.只是需要注意:
>
> ​	1 换元必换限,2求出原函数不用变量回代只需要将新的上下限带入公式.

```
1 换元. 根式=t, 再求出x的表达式, 在得出(根据凑微分)dx=dt
2换元必换限 x:a~b, t:根据x的换元表达式把ab带入得出的t就是了
3原式等
4不用回代,只需代入上下限就行.
```





![image-20220105191334446](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105191334446.png)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220105191407015.png" alt="image-20220105191407015" style="zoom:50%;" />







```
普通换元
```







<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220106182744636.png" alt="image-20220106182744636" style="zoom:50%;" />



```
分段函数换元
```

![image-20220106185219583](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220106185219583.png)





> 之所以步骤写的详细的原因是有一天我会忘记, 即使我不想记忆仍旧会会褪色我会忘记这些公式与步骤, that's why 我把他们写下,即使我某个时刻什么都不记得我也可以根据这笔记在过一遍.这就是人类为什么能取得超于前人的成就因为我们就站在巨人的肩膀上. \
>
> standing on the giant shoulders.这是图灵出版社出版的每一个书的扉页介绍,我很喜欢他们的计算机相关的书和封面对他们的封面好多是动物.

奇零倍偶

![image-20220106192058373](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220106192058373.png)





周期函数

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220106192255644.png" alt="image-20220106192255644" style="zoom:50%;" />

### 4分部

分部积分与之前不定积分一致. 对乘积后面带入上下区间, 替换后的积分也带入上下限.

![image-20220106192836215](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220106192836215.png)



//TODO 什么时候该用那种方式?

对于乘积形式的被积函数: 两个部分之间没有导数关系不用凑微分,没有根号不用换元,所以用分部积分



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108192949237.png" alt="image-20220108192949237" style="zoom:67%;" />



![image-20220108200320861](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108200320861.png)







<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108201652062.png" alt="image-20220108201652062" style="zoom:67%;" />



∫lnx可以作为公式记住,当然也不必.下面这道直接进行分部积即可





![image-20220108201859853](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108201859853.png)











## 四 广义积分 (improper integral)

广义积分又称为反常积分，所谓**反常积分**（字面意思）就是与正常积分不同，所谓正常积分（也叫**黎曼积分**）就是指区间有限、函数有界的定积分；所以广义积分就是指**区间无限**或**函数无界**的定积分。

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220106193059960.png" alt="image-20220106193059960" style="zoom:50%;" />

> 广义积分先代入区间试一下.



### 无穷限广义积分:积分区间无穷

一个重要的结论: 用于小题,区间有无穷





> 分为3种情况: 积分区间上限是无穷,积分区间下限是无穷,积分区间上下限都是无穷
>
> ​	依旧可以使用牛顿-莱布尼兹公式. 得出结果存在就是收敛, 结果无穷就是发散.(因为这里其实求极限的所以极限存在就是收敛,否则发散.)
>
> 结果存在为常数=收敛
>
> 结果为无限则=发散

![image-20220108203856375](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108203856375.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220107190653088.png" alt="image-20220107190653088" style="zoom:50%;" />



![image-20220107190724666](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220107190724666.png)







### 无界函数广义积分:被积函数无界 (瑕积分)

> 虽然有些函数区间并不存在无穷区间,但是带入被积函数后得到无穷大.这个就是瑕积分

一眼看过去好像没有瑕点,但是把他分隔开后

![image-20220108205504010](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108205504010.png)



瑕点: [a,b]区间内 a,b或者之间的c.

被积函数在[a,b]区间内取到无穷大,则成为该点瑕点.

计算方法与前面一致,使用牛顿莱布尼兹公式



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108205928433.png" alt="image-20220108205928433" style="zoom:67%;" />

前两种正常计算,第三中必须拆开计算



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108210236255.png" alt="image-20220108210236255" style="zoom:50%;" />







![image-20220107192634298](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220107192634298.png)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108212722639.png" alt="image-20220108212722639" style="zoom:67%;" />





### ⭐结论

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108204414948.png" alt="image-20220108204414948" style="zoom: 67%;" />



![image-20220108213254951](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108213254951.png)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108213528230.png" alt="image-20220108213528230" style="zoom:50%;" />

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108214148945.png" alt="image-20220108214148945" style="zoom:50%;" />





## 五 无定积分的应用

一般应用于大题. //哈哈,用来求曲边矩形的面积,和特殊几何体积



### 1面积

> 什么是曲边矩形?
>
> ​	三条边是直线,一个边是fx函数围成的曲线.
>
> 面积的值当然永远都是正值,所以给f(x)加上了绝对值,这样每一个被分割的小区间面积都是正值,他们加起来也都是正的.
>
> 

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220107195053734.png" alt="image-20220107195053734" style="zoom:50%;" />

#### X型曲边矩形面积

> x型的特点是a b两条直线垂直于x轴.

![image-20220107195430318](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220107195430318.png)





#### y型曲边矩形面积

> y型特征是[a,b]区间两边垂直于y轴
>
> 还要将y=fx函数转换为 : x=f(y)
>
> ​	例如y=2x+3, x=(y-3)/2

![image-20220108104609224](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108104609224.png)



#### x型区域面积

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108110854063.png" alt="image-20220108110854063" style="zoom: 67%;" />



它们都加了绝对值表示面积为正,所以f-g还是g-f应该无所谓.



#### Y型区域面积

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108110957165.png" alt="image-20220108110957165" style="zoom:67%;" />





### 2旋转体体积

> 求体积就是求 ∫a-b 横截面面积 dx
>
> ​	横截面就是一个圆,圆的面积就是πr^2, 求r^2就变得重要.
>
> 看下图,x是[a,b]变化的点,y是他的高度y=f(x)表示根据变化的x根据固定function得出的一个变化后的数值,就是他的高度. 也就是横截面圆的面积半径r. 求他的面积就是y^2

![image-20220108112008704](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108112008704.png)



> 再来看第二种y型的体积



要记得把y=f(x), 转换成x=φ(y)

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108115508517.png" alt="image-20220108115508517" style="zoom:67%;" />

例题

> 一般下都符合xy型,优先视为x型曲边矩形(好计算些),直接代入求积分.



![image-20220108153924064](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108153924064.png)







> 对于两个曲线围成的面积,也是优先视为x型,并用上面曲线-下面的曲线. 这道题区间范围[0,1].在区间内根号x > x^2所以用√x-x^2

![image-20220108154416782](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108154416782.png)



<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108154317142.png" alt="image-20220108154317142" style="zoom:50%;" />



> 下面这道例题是多个图像组合起来的面积. 一个曲线是cosx,一个是sinx. 所以把区间分为[0,π/4]和[π/4,π]
>
> 左边图像的面积:∫cosx-sinx, 右边是sinx-cosx. 再相加即可

![image-20220108154852491](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108154852491.png)



> 下面是一些体积的案例.

<img src="https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108160044438.png" alt="image-20220108160044438" style="zoom:80%;" />





![image-20220108160955250](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108160955250.png)

![image-20220108161604230](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220108161604230.png)





![image-20220109161633547](https://gitee.com/quanlongcs/pic-bed/raw/master/img/image-20220109161633547.png)
