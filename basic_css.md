# Learn Basic  CSS

```html
<style></style>								<!--添加样式表-->
<link rel="stylesheet" href="styles.css">		<!--链接样式表-->
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
											<!--使页面样式在移动设备、电脑上相似-->
<div></div>									 <!--用于设计布局-->	
<article></article>							  <!--包含多个具有相关信息的元素。-->
<hr>										<!--自闭合，分隔符-->
```



```css
/*几类选择器*/
element {								    /*元素选择器，指定元素设置属性添加样式,*/	
	styles	
}
.class-name {								/*类选择器*/
 	styles
}
#menu {									   /*id选择器*/
	styles
}
a:visited { 								/*伪选择器*/
    propertyName: propertyValue;
}
a:hover {									/*悬停伪选择器*/
    propertyName: propertyValue;
}
a:active { 									/*网页被点击时伪选择器*/
    propertyName: propertyValue;
}
selector1, selector2 {						/*选择多个元素时，用逗号隔开*/
  property: value;
}
.item p {								   /*选择类item下所有p元素*/
    styles
}

/* comment here */							/*注释格式*/
text-align: center;						     /*文本内容居中*/
width: 300px;							    /*宽度为300px*/
background-color: brown;					 /*设置背景颜色为棕色。*/
border-color: brown；					    /*边界颜色设置*/
width: 80%;								    /*当前元素的宽度为其父元素的80%*/
margin-left: auto;							/*左边距自动，元素向右靠齐*/
margin-right: auto;							/*右边距自动，元素向左靠齐*/
background-image: url(http://xxxxx)			  /*设置页面背景图片*/
display: inline-block;					      /*块级元素改成内联元素*/
padding: 20px;								/*内容和边界距离，内部距离*/
max-width: 500px;							/*最大宽度为500px*/
font-family: sans-serif;					 /*更改字体*/
font-style: italic；							/*字体为斜体*/
font-size: 40px;							/*字体尺寸为40px*/
```







