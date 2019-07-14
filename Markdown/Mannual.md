
Table of Contents
=================

   * [Markdown](#markdown)
    * [2.1 格式问题](#21-格式问题)
     * [2.1.1 文字段落](#211-文字段落)
         * [添加副标题](#2111-添加副标题)
             * [方法一 使用减号](#方法一--使用减号)
             * [方法二 使用减号和等号](方法二--使用减号和等号") 
         * [添加注释](#2112-添加注释)
             * [方法详解](#注释方法详解) 
         * [换行问题](#2113-如何换行)
             * [方法一  两段文字间两个空格再回车](#方法一--两段文字间两个空格再回车)
             * [方法二  两段文字间空一行](#方法二--两段文字间空一行)
             * [方法三 两段文字间添加标签](#方法三-两段文字间添加标签)
         * [代码块对齐方式](#2114-代码块对齐方式)
             * [方法详解](#代码块方法详解)  
     * [2.1.2 公式方程](#212-公式方程格式) 
         * [长公式](#2121-长公式)
             * [公式对齐](#公式对齐)
             * [CSDN特例](#CSDN中的对齐)
         * [公式组](#2122-公式组)
             * [公式组对齐](#公式组对齐) 
         * [分支公式](#2123-分支公式)
         * [公式编号](#2124-公式编号)  
     * [2.1.3 表格图片](#213-表格图形) 
         * [插入目录](#2131-插入目录)
             * [CSDN](#CSDN)
             * [GitHub](#GitHub)  
         * [树状目录](#2132-树状目录)  
         * [绘制表格](#2133-绘制表格)
             * [md原生](#md原生)
             * [html](#html)
             * [Excel表格导入](#Excel)  
         * [调整表格位置](#2134-调整表格位置)
         * [画流程图](#2135-画流程图)
         * [画函数图像](#2136-画函数图像)  
         * [图片相关](#2137-图片相关)
             * [插入图片](#插入图片)
             * [并排显示](#并排显示) 
         
      * [2.2 符号问题](#22-符号问题)  
         * [2.2.1 字母头顶加倒三角$\widehat f$](#221-字母头顶加倒三角如widehat-f)
         * [2.2.2 平均数符号$\overline x$](#222-平均数符号)
         * [2.2.3 等价于符号$\sim$](#223-等价于符号)
         * [2.2.4 添加微积分符号$\int$,$\mathrm{d}$ 和 $\partial$](#224-添加微积分符号)
         * [2.2.5 极限$\min \limits_{\lambda>0} f(x)$及其下标](#225-极限及其下标)  
         * [2.2.6 极限$\lim_{\epsilon \to 0}$及其下标](#226-极限及它下标)
         * [2.2.7 空心字母$\mathbb{R}$](#227-空心字母)
         * [2.2.8 梯度$\nabla$](#228-梯度)  
         * [2.2.9 变化量$\Delta$](#229-变化量)
         * [2.2.10 导数$f'(x_0)$](#2210-导数)
         * [2.2.11 向量$\vec{x_1}$和$\mathbf{x}$](#2211-向量) 
         * [2.2.12 矩阵符号](#2212-矩阵符号)  
         * [2.2.13 异或符号$\oplus$](#2213-异或符号)
         * [2.2.14 克罗内克乘积$\otimes$](#2214-克罗内克乘积)  
         * [2.2.15 阿达马乘积$\circ$](#1215-复合运算)
           
      * [2.3 参考](#23-参考)


#<div id='markdown'>Markdown</div> 
## <div id='21-格式问题'>2.1 格式问题</div>

### <div id="211-文字段落">2.1.1 文字段落</div>

#### <div id='2111-添加副标题'>+ 添加副标题</div>
+ <div id="方法一--使用减号">方法一 使用减号</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;采用`副标题文字 （换一行） ---`减号两个及以上；方法如下：

    ![Alt text]( ./Pictures/1.png "darknet-53")
      
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;效果如下：    
 
	#标题
	副标题文字 
	---	 
	
+ <div id="方法二--使用减号和等号">方法二 使用减号和等号</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;采用`=`和`-`分别表示主标题和副标题，且`=`个数大于两个，`-`个数大于三个；方法如下：  

  ![Alt text]( ./Pictures/2.png "darknet-53")  
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;效果如下：
  
	主标题
	===
	副标题
	----
	

#### <div id='2112-添加注释'>+ 添加注释</a>  

+ <div id="注释方法详解">方法详解</div>  
 [在Markdown中写注释](https://www.imooc.com/article/23400)

#### <div id='2113-换行问题'>+ 换行问题</a>

+ <div id="方法一--两段文字间两个空格再回车">方法一 两段文字间两个空格再回车</div>
  1.第一种方式换行  
  2.这是一个Markdown编辑器  

+ <div id="方法二--两段文字间空一行">方法二  两段文字间空一行</div>
  1.第二种方式换行
  
  2.这是一个Markdown编辑器

+ <div id="方法三-两段文字间添加标签">方法三 两段文字间添加标签</div> 
  输入：  
  `1.第三种方式换行</br>2.这是一个Markdown编辑器`  
  输出：  
  1.第三种方式换行</br>2.这是一个Markdown编辑器

#### <div id="2114-代码块对齐方式">+ 代码块对齐方式</div>
+ <div id="代码块方法详解">方法详解</div>

1. 采用两个`TAB`键来导入代码时,以居中为例；  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;直接在代码块前和后加入`<center>`和`</center>`,并且要与代码块空一行,默认为左对齐，右对齐还没找到实现方法：
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

### <div id="212-公式方程">2.1.2 公式方程</div>

#### <div id='2121-长公式'>+ 长公式</a>
+ <div id="公式对齐">公式对齐</div>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;无需对齐使用``multline``，需对齐使用``split``，换行使用``\\``，对齐使用``&``，示例如下：  

  ````    
  $$
  \begin{multline}
  x = a +b + c + \\
  d + e + f + g
  \end{multline}
  $$  
  ````
$$\begin{multline}
x = a +b + c + \\  
d + e + f + g
\end{multline}$$

  ````
  $$
  \begin{split}
  x =& a + b + c +\\
  	  &d + e + f + g
  \end{split}
  $$
  ````
$$\begin{split}
x =& a + b + c +\\
	&d + e + f + g
\end{split}$$  
 
+ <div id="CSDN中的对齐">CSDN特例</div>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CSDN_Markdown在对齐公式时的用法稍有不同，应该使用``eqnarray``，换行使用``\\``，对齐使用``&``，示例如下：  

  ````
  $$
  \begin{eqnarray}
  x =& a + b + c + \\
     & d + e + f + g
  \end{eqnarray}
  $$
  ````  
$$
\begin{eqnarray}
x =& a + b + c + \\
   & d + e + f + g
\end{eqnarray}
$$
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CSDN_Markdown好像又变了，``eqnarray``不能用，应该使用``aligned``，不管是多行公式还是公式组都可以使用这个，示例如下：  

  ````
  $$
  \begin{aligned}
  x =& a + b + c + \\
     & d + e + f + g
  \end{aligned}
  $$
  ````  
$$
\begin{aligned}
x =& a + b + c + \\
   & d + e + f + g
\end{aligned}
$$ 

#### <div id='2122-公式组'>+ 公式组</a>
+ <div id="公式组对齐">公式组对齐</div>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;需要对齐的公式组使用``align``，不需要对齐的公式组使用``gather``，示例如下：  
  
  ````
  $$
  \begin{gather}  
  x = 5 + 2 + 1 \\  
  y = x + 4
  \end{gather}
  $$
  ````
$$
\begin{gather}  
x = 5 + 2 + 1 \\  
y = x + 4
\end{gather}
$$  

  ````
$$
\begin{align}  
x &= 5 + 2 + 1 \\  
y &= x + 4
\end{align}
$$  
````
$$
\begin{align}  
x &= 5 + 2 + 1 \\  
y &= x + 4
\end{align}
$$ 

#### <div id='2123-分支公式'>+ 分支公式</div> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;分段函数通常使用cases次环境表示，示例如下：
  
````
$$
y = \begin{cases}
x,\quad x\leq 0\\
-x, \quad x > 0
\end{cases}
$$
````
$$
y = \begin{cases}
x,\quad x\leq 0\\
-x, \quad x > 0
\end{cases}
$$

#### <div id="2124-公式编号">+ 公式编号</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;只要在公式后添加`\tag(公式名字)`就可以在公式后面添加编号，详情如下：
    
``
$$\alpha=\frac{1}{u^Ty_k}, \beta=\frac{-1}{v^Ty_k}\tag{1.3}$$
``    

$$\alpha=\frac{1}{u^Ty_k}, \beta=\frac{-1}{v^Ty_k}\tag{1.3}$$

### <div id="213-表格图形">2.1.3 表格图形</div>

#### <div id='2131-插入目录'>+ 插入目录</div>
+ **<div id="CSDN">CSDN</div>**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;和大部分Markdown编辑器一样，直接使用`[TOC]`，可以自动生成目录，如下所示：
  
````markdown  
[TOC]  
# 大标题  
## 标题二  
一二三四五···  
## 标题三  
六七八九十···
````  
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;结果如下：  
![Alt text](Pictures/csdn.png)  

+ **<div id="GitHub">GitHub</div>**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GitHub使用的 Markdown 是Github Flavored Markdown，简称 GFM。其中并没有自动生成目录的功能。可以使用一个生成GFM目录的开源工具：[ekalinin/github-markdown-toc](ekalinin/github-markdown-toc)。该工具的使用方法如下(使用该工具时要关闭编辑好的markdown)文档，否则无结果）：  
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*1，安装，终端输入：*   

```  
\\Mac  
$ curl https://raw.githubusercontent.com/ekalinin/github-markdown-toc/master/gh-md-toc -o gh-md-toc  
$ chmod a+x gh-md-toc  
  
\\Linux 
$ wget https://raw.githubusercontent.com/ekalinin/github-markdown-toc/master/gh-md-toc
$ chmod a+x gh-md-toc
```  
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*2. 使用（STDIN，本地（LOCAL），远程（REMOTE））：*  
  
```
\\STDIN  
$ cat 目标文档位置 | ./gh-md-toc -  
\\LOCAL  
$ ./gh-md-toc 目标文档位置  
\\REMOTE  
$ ./gh-md-toc https://github.com/Roggu123/Algorithm/blob/master/MyNote/Optimise.md
```  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*3.实际过程与结果：*  
  
![Alt text](Pictures/Result1.png)  
![Alt text](Pictures/Result2.png)  
![Alt text](Pictures/Result3.png)  
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*4.将终端显示的结果粘贴到目标Markdown中（以本地文件为例）：*. 
  
![Alt text](Pictures/Result4.png)  
  
#### <div id='2132-树状目录'>+ 树状目录</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;我想将下图中的目录再划分为四大类（算法，数据，编程，数学），形成一个树状目录，也就是先划分出四个分支，然后每个分支再被划分若干分支。
![Alt text](Pictures/CatalogTree.png)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;查了很多资料都是生成文件树目录的，感觉无法套用，所以全部手工输入做了一个满足自己要求的树状目录。将如何输入其中一些符号的办法记录如下（我是Mac系统）：  

``shift``+``|``: | 目录左侧竖线  
``option``+``-``: –– 竖线旁边的横线（位于中间的长横线）  
``shift``+``-``: _ 位于下部的横线  
``-``: -- 位于中部的短横线  
最后我手工造出来的目录如下，输入三个 ` 构造一个代码块，然后就按下面所示的输入名称及横线，办法比较笨，但自认为还是比较简洁方便的。

#<center>Theory</center>
笔面试中的理论考察
-----------
```  
├── _算法  
|   |–– Algorithm ------------- 算法基础知识
|   |–– ROC_AUC --------------- ROC曲线与AUC详解
|–– _数据  
|   |—— Data ------------------ 数据   
├── _编程  
|   ├── Python ---------------- Python基础知识  
|   └── Input & Output -------- 输入输出函数详解  
├── _数学  
|   ├── Mathmetics ------------ 算法中涉及的数学知识  
```

####<div id='2133-绘制表格'>+ 绘制表格</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在markdown中绘制表格有三种方法如下：
  
+ **<div id="md原生">md原生</div>**

  ````
|		  |值类型 			|引用类型		 |   
|-------- |:---------:    |:-----:        |    
|定义		 |直接存储数据	 |持有数据的引用   |  
|存储		 |栈				|堆		       |
  ````
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;结果如下：

  |		  |值类型 			|引用类型		 |   
  |-------- |:---------:    |:-----:        |    
  |定义		 |直接存储数据	 |持有数据的引用   |  
  |存储		 |栈				|堆		       | 

+ **<div id="html">html</div>**  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;html表格的优势在于可以实现表格内换行，其它没变，就是加了个``<br>``。

  ````
  |		    |值类型.         			   |引用类型|   
  |-------- |:---------:    		  		 |:-----:|    
  |定义		 |直接存储数据	 		 		|持有数据的引用|  
  |存储		 |栈							   |堆|
  |例子		 |1. 数字数据类型<br>2.Boolean,Char,Date| 
  ````
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;结果如下：

|		     |值类型.         			 |引用类型  |   
|-------- |:---------:    		  		 |:-----:   |    
|定义		  |直接存储数据	 		 		|持有数据的引用|  
|存储		 |栈							   |堆. |
|例子		 |1. 数字数据类型<br>2.Boolean,Char,Date| 

+ **<div id="Excel">Excel表格导入</div>**
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;可以使用软件Typora实现这一功能。Typora[下载链接](https://www.typora.io/),软件无毒，体积小且免费。  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;操作步骤（Mac)：
  
1. 复制Excel表格里的内容；  
![Alt text](Pictures/3.png)  
2. 粘贴至Typora中，会显示表格，将其选中；  
![Alt text](Pictures/4.png)
3. 选择``复制为Markdown``；  
![Alt text](Pictures/5.png)
4. 在Markdown中粘贴代码；

 ```
 |      | 值类型                                    | 引用类型       |
 | ---- | ----------------------------------------- | -------------- |
 | 定义 | 直接存储数据                              | 持有数据的引用 |
 | 存储 | 栈                                        | 堆             |
 | 例子 | 1.   数字数据类型;<br>2.Boolean,Char,Date |                |

 ```
 结果如下：

 |      | 值类型                                     | 引用类型        |
 | ---- | ----------------------------------------- | -------------- |
 | 定义 | 直接存储数据                                 | 持有数据的引用   |
 | 存储 | 栈                                         | 堆             |
 | 例子 | 1.   数字数据类型;<br>2.Boolean,Char,Date    |                |
   
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;要实现表格内换行也是在Excel表格中输入时，添加标签``<b>``。
Windows下的操作步骤可参考这篇博文[快速将Excel表格转换为MarkDown表格 /Convert Excel to the MarkDown](https://steemit.com/cn/@jubi/excel-markdown-convert-excel-to-the-markdown)。  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;根据网上资料，还可以安装[exceltk](http://www.cnblogs.com/math/p/exceltk.html)，然后通过输入终端命令实现转换，个人实践发现exceltk在Mac里无法安装，所以就不演示了。
 

#### <div id='2134-调整表格位置'>+ 调整表格位置</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;表格默认是居左的，要调整表格居中，居右。可以分别用标签`<div align="center"></div>`和`<div center="right">...</div>`将表格括起来就好。具体示例如下（要输入表格时直接在文字后回车并在下一行输入表格，不需两个空格后回车）：  

  ```
  <div align="center">
  
  |		     |值类型 	    |引用类型		 |   
  |-------- |:---------:|:-----:     |    
  |定义		  |直接存储数据	 |持有数据的引用|  
  |存储		  |栈		    |堆		    |
  </div>
  ```  
结果如下
<div align="center">

|		     |值类型 	    |引用类型		 |   
|-------- |:---------:|:-----:     |    
|定义		  |直接存储数据	 |持有数据的引用|  
|存储		  |栈		    |堆		    |
</div>



#### <div id='2135-画流程图'>+ 画流程图</a>

**参考：**  
[Markdown快速入门](https://zhuanlan.zhihu.com/p/40446298)
  
#### <div id='2136-画函数图像'>+ 画函数图像</a>  
Markdown是画不了的，但可以通过一些网站如[desmos](https://www.desmos.com/calculator)画，然后插入图片。 

#### <div id='2137-图片相关'>+ 图片相关</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;参考[关于Markdown里的图片并排显示](https://blog.csdn.net/WMN7Q/article/details/73138326)进行总结。  

+ **<div id='插入图片'>插入图片</div>**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在Markdown中插入图片有两种方法如下：  

   1. 基础格式  
   `![Alt text](图片路径或链接)`  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;该方法比较简单且美观，但无法调整图片大小。  
   2. 调用标签  
   `<img src="图片路径或链接" width="宽度" height="高度"/>`  
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;该方法适合对图片进行调整，但比较麻烦且有时不美观，因此有时需在外嵌套标签`<div align="">..</div>`，`<figrure></figure>`等调整图片位置。  
   
+ **<div id='并排显示'>并排显示</div>**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;基础格式插入图片默认一行一张，目前没看到有调整办法。要想一行并排显示多张图片一般都采用标签的方式实现。

   1. 居中显示  
`<center class="half">...</center>`
   2. 左对齐显示  
`<figure class="half">...</figure>`
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;以上均为设置两张图片并排显示，可以通过修改为`class="third"`实现三张图片并排显示，其它的依次类推。通过`<center>`插入图片比较小，但默认居中较美观；通过`<figure>`插入图片可以调整大小，但不居中，可通过标签`<div align="center">...</div>`调整为居中。

# <div id="22-符号问题">2.2 符号问题</div>
![Alt text](https://img-blog.csdn.net/20170423152920434?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd2lyZWxlc3NfY29t/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)   
![Alt text](https://img-blog.csdn.net/20170423153258655?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd2lyZWxlc3NfY29t/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)  
![Alt text](https://img-blog.csdn.net/20170423153715939?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd2lyZWxlc3NfY29t/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast) 
### <div id="221-字母头顶加倒三角如widehat-f">2.2.1 字母头顶加倒三角$\widehat f$</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在字母前加 \hat,具体如下：  
<center>\$\hat f(x)$</center>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;结果显示为
$$\hat f(x)$$
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当只有一个字母时，此方法的显示为$\hat f$, 此时对 \hat 进行修改可以使倒三角位于字母正上方：  
<center>\$widehat f$</center>  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;结果显示为
$$\widehat f$$  
### <div id="222-平均数符号">2.2.2 平均数符号$\overline x$  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在字母前加 \overline,具体如下：  
<center>\$\overline x$</center>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;结果显示为
$$\overline x$$  

### <div id="223-等价于符号">2.2.3 等价于符号$\sim$</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;符号$\sim$可以表达很多意思，具体如下：

1. 可以表示等价于。以求极限为例，$x$等价于$sin(x)$可写成$x \sim sin(x)$，  
``$x \sim sin(x)$``$\rightarrow$ $x \sim sin(x)$   
2. 可以表示负样本，以贝叶斯公式为例，  
``$P(L|+)=\frac{P(+|L)P(L)}{P(+|L)P(L)+P(+|\sim L)P(\sim L)}$``$\rightarrow$ $P(L|+)=\frac{P(+|L)P(L)}{P(+|L)P(L)+P(+|\sim L)P(\sim L)}$ 

### <div id="224-添加微积分符号">2.2.4 添加微积分符号</div>
1. 积分符号  
``$\int_{k=1}^n$``$\rightarrow$ $\int_{k=1}^n$
  
2. 微分符号  
偏微分：``$\partial y$``  $\partial y$  
微分：``$\mathrm{d} y$``  $\mathrm{d} y$

### <div id="225-极限及其下标">2.2.5 极限$\min \limits_{\lambda>0} f(x)$及其下标</div> 
``$\min \limits_{\lambda>0} f(x)$``$\rightarrow$ $\min \limits_{\lambda>0} f(x)$  

### <div id="226-极限及它下标">2.2.6 极限$\lim_{\epsilon \to 0}$及其下标</div>  
``$\lim_{\epsilon \to 0}$`` $\rightarrow$ $\lim_{\epsilon \to 0}$

### <div id="227-空心字母">2.2.7 空心字母$\mathbb{R}$</div>   
``$\mathbb{R}$``$\rightarrow$ $\mathbb{R}$  
  
### <div id="228-梯度">2.2.8 梯度$\nabla$</div>  
``$\nabla$`` $\rightarrow$ $\nabla$  
  
### <div id="229-变化量">2.2.9 变化量$\Delta$</div>  
``$\Delta$`` $\rightarrow$ $\Delta$  

### <div id="2210-导数">2.2.10 导数$f'(x_0)$</div>
``$f'(x_0)$`` $\rightarrow$ $f'(x_0)$

### <div id="2211-向量">2.2.11 向量$\vec{x_1}$或$\mathbf{x}$</div>
向量有两种表示形式如下：  
``$\vec{x_1}$`` $\rightarrow$ $\vec{x_1}$  
或  
``$\mathbf{x}$`` $\rightarrow$ $\mathbf{x}$  

### <div id="2212-矩阵符号">2.2.12 矩阵符号</div>
**不带括号的矩阵**：  
  

```markdown
$$
 \begin{matrix}
   a & b & c & d & e\\
   f & g & h & i & j \\
   k & l & m & n & o \\
   p & q & r & s & t
  \end{matrix} 
$$
```  
结果如下：  
$$
 \begin{matrix}
   a & b & c & d & e\\
   f & g & h & i & j \\
   k & l & m & n & o \\
   p & q & r & s & t
  \end{matrix} 
$$  
**带中括号的矩阵**：  

```Markdown
$$
\left[
 \begin{matrix}
   a & b & c & d \\
   f & g & h & i \\
   \vdots & \cdots & \ddots & n \\
   p & q & r & s 
  \end{matrix} 
\right]
$$
```
结果如下：
$$
\left[
 \begin{matrix}
   a & b & c & d \\
   f & g & h & i \\
   \vdots & \cdots & \ddots & n \\
   p & q & r & s 
  \end{matrix} 
\right]
$$
**带大括号的矩阵**：  

```Markdown
$$
\left\{
 \begin{matrix}
   a & b & c & d & e\\
   f & g & h & i & j \\
   k & l & m & n & o \\
   p & q & r & s & t
  \end{matrix} 
\right\}
$$
```
结果如下：
$$
\left\{
 \begin{matrix}
   a & b & c & d & e\\
   f & g & h & i & j \\
   k & l & m & n & o \\
   p & q & r & s & t
  \end{matrix} 
\right\}
$$

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;矩阵中加省略号及横线等更多详情见[使用MarkDown画矩阵](https://www.jianshu.com/p/08cbe54a5f33)。  

## <div id="2213-异或符号">2.2.13 异或符号$\oplus$</div>  
`\mathbf{A}\oplus\mathbf{B}`$\rightarrow$ $\mathbf{A}\oplus\mathbf{B}$  

## <div id="2214-克罗内克乘积">2.2.14 克罗内克乘积$\otimes$</div>  
`\mathbf{A}\otimes\mathbf{B}`$\rightarrow$ $\mathbf{A}\otimes\mathbf{B}$ 

## <div id="1214-复合运算">2.2.14 阿达马乘积$\circ$</div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;阿达马乘积有时也称为复合运算。  
`\mathbf{A}\circ\mathbf{B}`$\rightarrow$ $\mathbf{A}\circ\mathbf{B}$
 
## <div id="23-参考">2.3 参考</a>  
+ **格式**  
[1].[Markdown语法整理](https://guo365.github.io/study/Markdown.html#3)  
[2].[CSDN-Markdown语法集锦](https://blog.csdn.net/bone_ace/article/details/46400975)  
[3].[Markdown中Latex 数学公式基本语法](https://blog.csdn.net/u014630987/article/details/70156489)  
[4].[markdown 数学公式Latex语法](https://juejin.im/post/5af93ec6518825428b38e7f4)  
[5].[数学、物理中常用的希腊字母怎么读？](https://www.zhihu.com/question/23655549)  
[6] WMN7Q.[关于Markdown里的图片并排显示](https://blog.csdn.net/WMN7Q/article/details/73138326)

+ **符号**  
[1] xxq2dream.[使用MarkDown画矩阵](https://www.jianshu.com/p/08cbe54a5f33)  
[2] 一生之寄.[数学符号中各种“约等于”表示符号有没有不同？有什么不同？](https://www.zhihu.com/question/33314612)  
[3] Milton.[深入浅出数据分析](https://github.com/Roggu123/DataAnalysis/blob/master/References/深入浅出数据分析中文版.李芳.扫描版.pdf)  
[4] Leon.[Markdown语法和LaTeX数学记号速查手册](http://www.domuse.com/markdown-and-latex-equation-handbook.html)  
[5] codeep.[Cmd Markdown 公式指导手册](https://www.zybuluo.com/codeep/note/163962#6逻辑运算符)





 


 


