# Learn CSS Variables

```css
/*选择所有元素*/
* {
    styles;
}

--variable-name: value;							/*设置变量*/
var(--variable-name)							/*引用变量*/
align-items: flex-end;							/*底部对齐*/
justify-content: space-evenly;					/*均匀分布*/
var(--variable-name, fallback-value)			/*第一个变量出问题时使用回调值*/

/*从一个颜色渐变到另一个颜色*/
gradient-type(
  color1,
  color2
);
/*线性渐变*/
linear-gradient(
	var(--building-color1),
	var(--window-color1)
);

gradient-type(
  color1,
  color2 20%,
  color3
);
/*颜色突然转变*/
linear-gradient(
  var(--first-color) 0%,
  var(--first-color) 40%,
  var(--second-color) 40%,
  var(--second-color) 80%
);

repeating-linear-gradient(
  var(--first-color) 0%,
  var(--first-color) 40%,
  var(--second-color) 40%,
  var(--second-color) 80%
);

/*设置渐进的方向*/
gradient-type(
  direction,
  color1,
  color2
);

gradient1(
  colors
),
gradient2(
  colors
);

/*放射性渐变*/
background: radial-gradient(
	circle closest-corner at 15% 15%,
    #ffcf33 0%,
    #ffcf33 20%,
    #ffff66 21%,
    #bbeeff 100%
  )
```

