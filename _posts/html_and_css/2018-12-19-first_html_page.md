---
layout: subpage
category: html_and_css
mastheadclass: others
title: learn html$css
---
<h1>h1 定义标题 从1到6 一般自动在标题、段落前后加空行</h1>
<br/> <h1> br/ 定义换行符加上/更加保险</h1>
<p>p 定义段落</p>
<p> html文档 也被称为网页 一般由成对的标签构成</p>
<br/>

<p >标签同样存在属性，属性是键值对 name=‘value’ 来让我举个栗子</p>

<h1 align="center" > align="center" 居中放置标题</h1>
<hr>
<p>hr 创建水平分割线</p>

<p>当显示页面时，浏览器会移除源代码中多余的空格和空行。所有连续的空格或空行都会被算作一个空格</p>




<p style="background-color: #333;color: white;text-align: center;">
<!-- 	<h1>春晓</h1> -->
    春眠不觉晓，<br>
    处处闻啼鸟。<br>
    夜来风雨声，<br>
    花落知多少。<br>
</p>
<code>
	if
	else code这里面不会保留多余的换行
</code>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
五十年来，WWF 一直致力于保护自然界的未来。
世界领先的环保组织，WWF 工作于 100 个国家，
并得到美国一百二十万会员及全球近五百万会员的支持。
</blockquote>
<a href="https://www.baidu.com" target="_blank"> target =_blank属性使得在新的标签页打开我们的页面</a>

<a name='tips'>在同一个文档中创建锚 ，可以在同一个html中进行定位</a>
<br/>
<a href="#tips">回到之前的tips锚</a>

<hr>

<p>图片<img src="{{site.baseurl}}/image/html&css/eg_background.gif"  width="200" height="200" alt="用来检测图片位置" align="bottom">在底部</p>
<p>图片<img src="{{site.baseurl}}/image/html&css/eg_background.gif" width="200" height="200" alt="用来检测图片位置" align="top">在上面</p>
<p>图片<img src="{{site.baseurl}}/image/html&css/eg_background.gif" width="200" height="200" alt="用来检测图片位置" align="middle">在底部</p>
<p><img src="{{site.baseurl}}/image/html&css/eg_background123.gif" width="200" height="200" alt="用来检测图片位置" align="middle">图片失效后显示alt信息</p>
<p>图片默认的对齐方式是bottom</p>
<hr>
<p>table 标签的作用下创建表格，tr行 td 填充的数据，相当于列<br/>
	用border属性定义边框<br/>
	th为表头标签在table标签里定义，其实作用跟td差不多，就是换了个名字区别一下

</p>
<table border="2"> 
	<th>1</th>
	<th>2</th>
<tr>
	<td>row1 cell1</td>
	<td>row1 cell2</td>
	<td> </td>
</tr>
	<tr>
	<td>row2 cell1</td>
	<td>row2 cell2</td>
</tr>
</table>

