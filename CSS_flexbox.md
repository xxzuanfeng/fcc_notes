# Learn CSS Flexbox

```css
box-sizing: content-box;								/*默认conten-box,当元素指定宽度时，仅仅是指内容，设置padding和border后，元素宽度增加*/
box-sizing: border-box;									/*包括padding和border，设置后内容缩小来适应宽度*/
text-transform: uppercase;								/*文本改为大写*/
display: flex;										 	/*Flexbox 一维CSS布局，控制项目在容器内间隔和对齐方式*/
flex-direction: row;									/*默认，水平轴，从左到右*/
flex-direction: row-reverse;							/*水平轴，从右到左*/
flex-direction: column;									/*垂直轴，从上到下*/
flex-direction: column-reverse;							/*垂直轴，从下到上*/
flex-wrap: wrap;										/*容器太小时，换行*/
flex-wrap: nowwrap;										/*保持不变*/
justify-content: center;								/*定义沿主轴（main axis）定位*/
align-items: center;									/*定义沿横轴（cross axis）定位*/
object-fit: cover;										/*保持纵横比，填充容器，进行裁剪以适应*/

/*元素之间间隔*/
gap: 17px;
row-gap: 17px;
column-gap: 17px;

border-radius: 10px;									/*边界平滑*/

/*选择容器中最后元素的后面一个*/
.container::after {
  content: "";
  width: 860px;
}
```

c