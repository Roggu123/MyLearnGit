# Markdown 
## 2.1 问题积累
### 2.1.1 如何换行
#### 方法一  两段文字间两个空格再回车
1.第一种方式换行  
2.这是一个Markdown编辑器
#### 方法二  两段文字间空一行
1.第二种方式换行

2.这是一个Markdown编辑器
####  方法三 两段文字间添加标签<br/></br>
<br/>1.第三种方式换行</br>2.这是一个Markdown编辑器
### 2.1.2 代码块的对齐方式
#### 2.1.2.1 方法详解
1. 采用两个`TAB`键来导入代码时,以居中为例；  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;直接在代码块前和后加入`<center>`和`</center>`,并且要与代码块空一行,默认为左对齐，右对齐还没发现怎么实现：
<center>

		<center>
		
		printf("Hello, world");  
		printf("Hello, Markdown");
		printf("Hello, Macdown");
		
		</center>		
</center>
2. 采用两个```来导入代码块时；  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;直接在代码前加入若干TAB键来调整代码位置，左中右都可以实现：

```python
				printf("Hello, world");  
				printf("Hello, Markdown");
				printf("Hello, Macdown");
```
#### 2.1.2.2 参考
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;无参考，自己研究体会出来的。
### 2.1.3 如何添加副标题
1. 采用`副标题文字 （换一行） ---`减号两个及以上；如下所示：
 
	#标题
	副标题文字 
	---
	![Alt text]( ./1.png "darknet-53")  

2. 采用`=`和`-`分别表示主标题和副标题，且`=`个数大于两个，`-`个数大于三个；如下所示：  
	主标题
	===
	副标题
	----
	![Alt text]( ./2.png "darknet-53")

### 2.1.4 如何添加注释  
#### 2.1.4.1 方法详解  

#### 2.1.4.2 参考  
[在Markdown中写注释](https://www.imooc.com/article/23400)

### 2.1.5 如何插入目录
#### 2.1.5.1 csdn

#### 2.1.5.2 github
参考：[如何实现Github markdown 目录/页内跳转？](https://www.zhihu.com/question/58630229)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[github-markdown-toc](https://github.com/ekalinin/github-markdown-toc#installation)

### 2.1.6 字母头顶加倒三角如$\widehat f$
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在字母前加 \hat,具体如下：  
<center>\$\hat f(x)$</center>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;结果显示为
$$\hat f(x)$$
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当只有一个字母时，此方法的显示为$\hat f$, 此时对 \hat 进行修改可以使倒三角位于字母正上方：  
<center>\$widehat f$</center>  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;结果显示为
$$\widehat f$$
### 2.1.7 添加微积分符号
**方法详解**  

**参考**  
[Markdown中Latex 数学公式基本语法](https://blog.csdn.net/u014630987/article/details/70156489)
 


 


