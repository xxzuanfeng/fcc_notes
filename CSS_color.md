# Learn CSS Colors

```css
margin: 10px auto;								  /*第一个值顶部和底部，第二个值左边和右边*/
background-color: rgb(red, green, blue); 			   /*rgb函数*/
/*---------------------------------------三原色-----------------------------------------*/
rgb(255, 0, 0)										/*red-红*/
rgb(0, 255, 0)										/*green-绿*/
rgb(0, 0, 255)										/*blue-蓝*/
/*--------------------------------------次生色，两个原色组合------------------------------*/
rgb(255, 255, 255)									/*red+green+blue=white 红+绿+蓝=白*/
rgb(255, 255, 0)									/*red+green=yellow 红+绿=黄色*/
rgb(0, 255, 255)									/*green+blue=cyan 绿+蓝=青*/
rgb(255, 0, 255)									/*red+blue=magenta 红+蓝=品红*/
/*--------------------------------------三次色，原色和接近的次生色组合--------------------*/
rgb(255, 127, 0)									/*red+yellow=orange 红+黄=橘色*/
rgb(0, 255, 127)									/*green+cyan=spring green 绿+青=春绿*/
rgb(127, 0, 255)									/*magenta+blue=violet 品红+蓝=蓝紫色*/
rgb(127, 255, 0)									/*green+yellow=chartreuse green 绿+黄=淡黄绿*/
rgb(0, 127, 255)									/*blue+cyan=azure 蓝+青=天蓝色*/
rgb(255, 127, 0)									/*red+magenta=rose 红+品红=玫瑰红*/
/*----------------complementary-colore 互补颜色-------------------*/
rgb(255, 0, 0)							/*红青为互补色，挨着时非常明亮，让人分心，作为背景时难以阅读。*/
rgb(0, 0, 255)
/*-------------------hex values-7F为中间值------------------------------------*/
#FF0000									/*red红色*/
#00FF00									/*green绿色*/
#0000FF									/*blue蓝色*/
/*
-----HSL 0-360:hue(色调) 0-100%:saturation(饱和度) 0-100%:lightness(亮度)------
hue: 0degrees red红色  120degrees green绿色  240degrees blue蓝色
saturation: 0% gray -- 100% pure color
lightness: 0% black -- 50% neutral -- 100% white
*/

linear-gradient(gradientDirection, color1, color2, ...);			/*gradientDirection 梯度方向*/
linear-gradient(90deg, rgb(255, 0, 0), rgb(0, 255, 0))；				/*从红到绿渐变*/
linear-gradient(90deg, red 90%, black);								/*红色占90%，再转变*/
opacity: 0-1.0;													 /*不透明度，0为不透明，1.0为完全透明*/
rgba(redValue, greenValue, blueValue, alphaValue);					/*alpha用于设置不透明度，0为不透明，1.0为完全透明*/
display: inline-block;											/*设置元素显示未内联元素*/
border-left-width: 10px;										/*元素边框宽度为10px*/
border-left-style: solid;										/*元素边框样式为实线*/
border-left-color: black;										/*边框颜色为黑色*/
border-left: width style color;									/*左边框快捷键，宽度、样式、颜色*/
box-shadow: offsetX offsetY color;								/*添加阴影，offsetX正向右偏、负向左偏，offsetY正向下、负向上*/
box-shadow: offsetX offsetY blurRadius color;					/*blurRadius, 模糊系数，值越大越模糊*/
box-shadow: offsetX offsetY blurRadius spreadRadius color;		/*spreadRadius 扩散系数，值越大越分散*/
```

