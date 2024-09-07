# Learn HTML Forms

```css
vh								/*窗口高度，1vh=1%窗口*/

rem								/*相对html根元素，与html字体大小有关*/
p:last-of-type { }				/*伪类选择器，选则p元素最后一个*/
width: unset;					/*移除之前设置的样式*/
vertical-align: middle;			/*调整垂直位置*/
input[name="password"]			/*属性选择器，通过属性选择元素*/
```



```html
<form action='https://register-demo.freecodecamp.org' method="POST"></form> <!--以POST方法发送到action中URL*/-->
<input type="submit" value="Submit">					<!--提交距离最近的form表单-->
<input type="password" minlength=8>						<!--长度不能小于8-->
<input type="password" pattern="[a-z0-5]{8,}" />		<!--pattern匹配正则表达式-->	

<input type="radio" name="account-type" checked/>		<!--单选按钮使用相同的name关联，checked属性默认选择	-->
<input type="radio" name="account-type"/>
<input type="file" />									<!--上传一个文件-->
<input type="number" min="13" max="120" />				<!--限制大小-->

<select>												<!--下拉选项,value为提交的值-->
    <option value=1></option>
    <option value=2></option>
</select>

<textarea id="bio" rows=3 cols=30></textarea>				<!--接收多行文本-->
```

