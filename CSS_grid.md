# Learn CSS Grid

```html
<img src="xxx" laoding="lazy">							<!--lazy延迟加载图像资源-->
```



```css
display: grid;											/*网格布局*/
grid-template-columns: 1fr 94rem 1fr;						/*生成3列，fr为剩余空间*/
row-gap: 3rem;												/*添加行间距*/
grid-column: 2 / 3;										/*第2列开始，第3列结束*/
grid-template-columns: repeat(2, 1fr);						/*repeat()函数重复内容*/
object-fit: cover;										/*cover表示元素填满容器，根据需要裁剪，保持纵横比*/
grid-auto-flow: column;									/*根据需要创建新的列或行，第二个参数是dense*/
grid-auto-columns: 1fr;									/*默认设置*/
align-items: center;									/*按列对齐*/
justify-items: center;									/*按行对齐*/
letter-spacing: 0.6px;									/*字母间隔*/
column-width: 25rem;									/*把元素分成几列*/

/*伪选择器，第一段头字母设置字体大小、颜色*/
.first-paragraph::first-letter {						
  font-size: 6rem;
  color: orangered;
}
list-style-type: none;									/*取消列表前面的远点*/
place-items: center;									/*可以同时设置align-items和justify-items*/
```

