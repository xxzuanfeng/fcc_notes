# Learn Intermediate CSS

```css
* {													/*指定的宽度和高度包含padding和border */
	box-sizing: border-box;	
}

position: static;									/*默认，不能通过或left、top、right、bottom改变位置*/
position: absolute;									/*相对父元素，由left、top、right、bottom决定*/
position: relative;									/*相对原来位置*/
position: sticky;
position: fixed;									/*固定在页面上，悬浮窗类似*/
transform: rotate();								/*旋转角度*/
transform: scale();
transform: skew();
transform: matrix();
z-index: -1;										/*元素重叠顺序，数值越大越在上面*/
```

