<center>web前端笔记</center>

# HTML+CSS篇

## 吃尺寸大小

**width和height默认值为auto

auto和%区别：

​	1、auto：会将元素撑开至整个父元素width，但是会减去margin+padding+border

​	2、%：会强制将元素变成父元素一样的宽度，并且额外的空间（margin+padding+border）会加到width上

## 单位

绝对单位：不会因为其他元素的尺寸变化而变化

相对单位：没有一个固定的度量值，而是由其他元素尺寸来决定的相对值

​	px：像素  ==》绝对单位

​	vw：1%	视口（浏览器可视区域）的宽度

​	vh：1%	视口（浏览器可视区域）的高度

​	%	相对于父元素的宽度或者字体大小

## 元素之间的转换

块级元素特点：

​	1、总是在新行上开始（独占一行）

​	2、高度和行高以及内外边距都是可控制的

​	3、宽度默认就是100%

行内元素特点：

​	1、和其他元素都在一行显示（不独占一行）

​	2、高、行高以及顶部和底部的边距不可修改的

​	3、宽度就是他文字的宽度，不可修改的

行内块元素特点：

​	1、和其他元素都在一行显示（不独占一行）

​	2、高、行高以及顶部和底部的边距可修改的

​	3、宽度就是他文字的宽度，可修改的

元素转换属性：

```css
display:none		/*默认是为none（隐藏）*/
display: block   	/*转换成块*/	
display: inline		/*转换成行内*/
display: inline-block	/*转换成行内块*/
```

## 字体样式

```css
字体样式：font-family
字体大小：font-size: 16px;
字体粗细：font-weight: 100-900;
字体颜色：color: red;
首行缩进：text-indent: 30px;
文本水平对齐：text-align:left;	/*left right center*/
文本装饰：text-decoration: line-through;			/*默认值：none 删除线：line-through 下划线：underline*/
```

