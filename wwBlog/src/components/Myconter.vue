<template>
	 <div class="container-right">
	        <!--  文章列表  -->
	            <div class="blog">
	                <div class="title">关于HTML能做什么</div>
	                <div class="date">2022-1-22</div>
	                <div class="desc">HTML是超文本标记语言，是一个网站页面的主要内容和主体框架。主要用来实现静态页面，目前我们看到的文字、图片、动画、声音、表格、超链接等网页元素都是通过HTML实现的。HTML是由各种标签组成的，所学习HTML就是在了解HTML主体框架的结构基础上学习各种标签的使用方法。</div>
	                <a class="detail"  href="article.html">查看正文 &gt;&gt</a>
	            </div>
	            <div class="blog">
	                <div class="title">关于CSS能做什么</div>
	                <div class="date">2022-1-23</div>
	                <div class="desc">CSS是层叠样式表，主要用来控制调整网页的样式，它与网页的结构和内容没有关系，仅仅是通过不同语义的标签来调整网页内容的不同表现样式。在网页上实现CSS样式调整一般有两种方式：内嵌式，将CSS代码集中写到HTML文档的头部标签中，并用style标记定义，一般位于head标记中的title标记之后，简而言之就是直接在THML文件中直接添加CSS样式的方式；嵌入式，是将所有的样式放在一个或多个以CSS为拓展名的外部样式表文件中，通过标记将外部样式表文件链接到HTML文件中，简而言之就是HTML文件域CSS文件单独存在，再通过Link的方式将CSS所写的样式添加到HTML中。
	                </div>
	                <a class="detail"  href="article.html">查看正文 &gt;&gt</a>
	            </div>
	            <div class="blog">
	                <div class="title">关于JS能做什么</div>
	                <div class="date">2022-1-24</div>
	                <div class="desc">JavaScript是一种完整的网页脚本语言，有自己独立的语法，可以完成复杂的程序逻辑，而HTML和CSS仅仅是标记语言，不具备编程语言的程序逻辑。JavaScript主要负责网页的各式各样的动态功能，因此可以为用户提供更流畅美观的页面浏览效果，以及添加页面交互行为，给用户更好的视觉和使用体验。JavaScript的工作原理是通过在HTML网页中直接嵌入JS脚本，可以实现相应浏览器时间，读写HTML元素内容，更改HTML元素样式等功能。
	                </div>
	                <a class="detail" href="article.html">查看正文 &gt;&gt</a>
	            </div>
	        </div>
</template>

<script>
</script>

<style>
	
.container-right{
	    height: 95%;
	    width:1000px;
	    overflow: auto ;
	    background-color:#9fc4f2;
	    border-radius: 20px;
		position: absolute;
		left:600px;
		top:125px;
		opacity: 0.7;
	}
.blog{
    width:100%;
    /*上下左右边距*/
    padding: 30px 20px;
    /*底部边界虚线：黑色*/
    border-bottom: 2px solid #000;
}
.blog .title{
    color:black;
    /*字体大小*/
    font-size: 20px;
    /*字体粗细程度*/
    font-weight: 700;
    /*居中*/
    text-align: center;
    padding: 10px 0;
}
.blog .date{
    color: #008000;
    margin-top: 10px;
    text-align: center;

}
.blog .desc{
    color:#000;
    /*有两空格，首行缩进*/
    text-indent: 2em;
    /*上外边距：10像素的空白*/
    margin-top: 10px;
	font-size:16px;
}
.blog .detail{
    /*默认行展示，改为块展示*/
    display: block;
    width: 120px;
    height: 40px;
    line-height: 40px;
    color: black;
    text-align: center;
    text-decoration: none;
    margin: 10px auto 0 auto;
    border: 2px solid black;
    /*给颜色上加过滤效果，动画的持续时间*/
    transition: all .5s;
}
/* :hover伪类选择器，完整的意思：.blog下的 .detail在鼠标划过时，应用该样式*/
.blog .detail:hover{
    background-color:#000;
    color: #fff;
}
</style>