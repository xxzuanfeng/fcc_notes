# Learn CSS Animation

```css
transform-origin: 0% 0%;						/*应用CSS执行变换的点*/
transform: rotate(60deg);						/*围绕变换点旋转60度*/

/*定义动画，内容为起点和终点*/
@keyframes wheel {
   0% {
     transform: rotate(0deg);
   }
   100% {
     transform: rotate(360deg);
   }
}

animation-name: wheel;							/*应用上述动画*/
animation-duration: 10s;						/*动画持续时间*/
animation-iteration-count: infinite;			/*动画重复次数，无数次*/
animation-timing-function: linear;				/*动画形式，linear线性均匀*/
animation-timing-function: ease-in-out;			/*动画看起来更加自然*/
								
```

