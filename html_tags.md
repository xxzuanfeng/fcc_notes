# HTML tags

```html
<h1>This is a main heading</h1>					  <!--标题元素，用于网页的主标题-->
<h2>second most important heading element</h2>	    <!--标题元素，重要程度依次递减-->
<h3>third most important heading element</h3>
<h4>fourth most important heading element</h4>
<h5>fifth most important heading element</h5>
<h6>least important heading element</h6>
<p>paragraph of text</p>						 <!--文本元素-->
<!--content-->									<!--注释，可跨行-->

<!--用于表示HTML文档正文的主要内容。主元素中的内容应该是文档独有的，不应在文档的其他部分重复。-->
<main></main>

<img>													  <!--添加图片，只有开始标记，没有结束标记-->
<img src="url">											   <!--src属性指定图片的URL-->
<img src="url" alt="text">								    <!--图片加载失败时显示-->

<!--锚元素，链接到其他页面,text为链接文本，__blank表示在新标签中打开链接--> 
<a href="url" target="_blank">text</a>		

<section></section>										    <!--语义元素，定义文档中节，章节、页眉、页脚等-->

<!--无序列表-->
<ul>													   
    <li></li>
    <li></li>
</ul>

<figure></figure>										    <!--自包含内容，允许标题与图像关联-->
<figcaption></figcaption>									<!--图形标题元素，用于描述图片-->
<em></em>												   <!--强调指定单词或者句子-->
<ol>													   <!--有序列表-->
  <li></li>
  <li></li>
  <li></li>
</ol>
<strong></strong>											<!--表示某些文本具有很强的重要性或紧迫性-->

<!--用于获取用户信息，姓名、电子邮件等,action表示用户把数据发送到何处-->
<form action="/root"></form>								 

<!--从form表单中输入数据,type属性表示输入数据的类型,为了使action属性中指定位置访问表单数据，为文本字段指定一个name属性，分配值表示正在提交的数据，placeholder为占位符,required表示输入不能为空-->
<input type="text" name="name" placeholder="占位符" required>	

<button></button>											<!--创建可点击的按钮-->

<!--单选按钮，把输入和文本链接起来，id属性唯一,name、value为表单获取数值-->
<label><input type="radio" id="text" name="xxx" value="xxx">text</label>

<fieldset></fieldset>										<!--块级元素，把输入和标签组合在一起-->
<legend></legend>											<!--fieldset元素内容的标题-->
<input checked type="checkbox">text							  <!--多选框输入,默认选择-->

<!--定义文档或节的页脚。页脚通常包含有关文档作者、版权数据、使用条款链接、联系信息等信息。-->
<footer></footer>

<head></head>												<!--包含文档的元数据，如标题、样式表链接和脚本-->

<!--title元素决定了浏览器在页面的标题栏或选项卡中显示什么。-->
<title></title>			

<html lang=en></html>										<!--根元素，包含所有内容,lang表示语言-->
<!DOCTYPE html>												<!--声明，文档为html5-->
<meta charset="uft-8">										<!--页面编码方式-->
```

