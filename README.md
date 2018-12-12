GitHub基本操作（大标题）
======
规范的README文件开头都写上一个标题，这被称为大标题。在文本下面加上 等于号 = ，那么上方的文本就变成了大标题。等于号的个数无限制，但一定要大于0个。

Github基本操作（中标题）
----
在文本下面加上 下划线 - ，那么上方的文本就变成了中标题，同样的 下划线个数无限制。 
除此之外，你也会发现大、中标题下面都有一条横线，没错这就是 = 和 - 的显示结果。如果你只输入了等于号=，但其上方无文字，那么就只会显示一条直线。如果上方有了文字，但你又只想显示一条横线，而不想把上方的文字转义成大标题的话，那么你就要在等于号=和文字之间补一个空行。 （暂未实现） 
除此以外，关于标题还有等级表示法，分为六个等级，显示的文本大小依次减小。不同等级之间是以井号  #  的个数来标识的。一级标题有一个 #，二级标题有两个# ，以此类推。  
# 一级标题 
## 二级标题  
### 三级标题 
#### 四级标题  
##### 五级标题 
###### 六级标题 
实际上，前文所述的大标题和中标题是分别和一级标题和二级标题对应的。即大标题大小和一级标题相同，中标题大小和二级标题相同。  
# 显示文本  
### 普通文本  
直接输入的文字就是普通文本。需要注意的是要换行的时候不能直接通过回车来换行，需要使用\<br>、(或者\<br/>)、(两个空格+回车)、(tab+回车)。也就是html里面的标签。事实上，markdown支持一些html标签，你可以试试。当然如果你完全使用html来写的话，就丧失意义了，毕竟markdown并非专门做前端的，然而仅实现一般效果的话，它会比html写起来要简洁得多得多啦。\<br>前加了反斜杠 \ 。目的就是像其他语言那样实现转义，也就是 <  的转义。 
此外，要显示一个超链接的话，就直接输入这个链接的URL就好了。显示出来会自动变成可链接的形式的。
### 显示空格的小Tip
　默认的文本行首空格都会被忽略的，但是如果你想用空格来排一下版的话怎么办呢，有个小技巧，那就是把你的输入法由半角改成全角就OK啦。 
### 单行文本  
使用两个Tab符实现单行文本。<br>   
    大家好，我是渣渣辉。(暂未实现)    
本文部分内容转载自 http://blog.csdn.net/guodongxiaren/article/details/23690801 ,主要是熟悉GitHub的一些基本操作。
