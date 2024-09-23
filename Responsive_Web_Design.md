# Learn Responsive Web Design

```css
box-sizing: inherit;							/*继承父元素的值*/
::before;										/*创建一个伪元素为所选元素的第一个子元素*/
::after;										/*创建一个微元素为所选元素的最后一个子元素*/
content:"";										/*用于设置和覆盖元素的内容*/

/*媒体查询，有条件的应用CSS，通常使用最大宽度和最小宽度根据视口宽度来应用CSS*/
@media (max-width: 960px) {
  .card {
    padding: 2rem;
  }
}

overflow: hidden;								/*隐藏超出视口宽度的元素*/
```

