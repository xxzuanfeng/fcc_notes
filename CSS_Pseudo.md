# Learn CSS Pseudo Selectors

```html
<div id="years" aria-hidden=true></div>					<!--隐藏元素-->
<table></table>										<!--表格-->
<caption></caption>									<!--表头，描述表格-->
<thead></thead>										<!--表格头-->
<tbody></tbody>										<!--表格内容-->
<tr></tr>											<!--表格行-->
<td></td>											<!--数据单元格-->
<th></th>											<!--标题单元格-->
```

```css
/*选择所有span中报刊sr-only的类*/
span[class~="sr-only"] {
  border: 0;
}
clip: rect(1px, 1px, 1px, 1px);						/*定义元素可视部分*/
clip-path: inset(50%);								/*定义clip 形状*/
:first-of-type										/*匹配伪选择器的第一个元素*/
:last-of-type										/*匹配选择器的最后一个元素*/
calc(100% - 20px);									/*calc()函数进行数值计算*/
span[class]											/*选择所有拥有class属性的span元素*/
span:not(.sr-only)									/*定位不匹配选择器的元素*/
!important											/*不管顺序或指定，一直适用*/
border-collapse: collapse;							/*相邻单元格边框折叠成一个*/
vertical-align: top;								/*垂直方向顶端对齐*/
```

