<template>
	<div class="hr" @click="onmygod">
		<div class="lg"></div>
		<span>欢迎来到我的博客~</span>
		<div class="nav">
			<ul>
				<li class="ll"><a href="#">主页</a></li>
				<li><a href="#">写博客</a></li>
				<li><a href="#">注销</a></li>
			</ul>
		</div>
	</div>
</template>

<script>
	
</script>

<style>
	html,body{
		background-image: url(../assets/11.jpg);
		background-repeat: no-repeat;
		background-size: 100% 100% ; 
		overflow:auto;
		height: 105%;
		margin:0
	}
	.hr{
		height: 65px;
		border-radius: 25px;
		height: 80px;
		border:1px solid #fff;
		background-color: #19305f;
		opacity: 0.6;
	}
	.lg{
		width: 80px;
		height: 80px;
		background-size: 100% 100%;
		float:left;
		border-radius: 50%;
		background-image: url(../assets/dog.jpg);
		margin-left:140px;
	}
	ul{
		width: 300px;
		position: absolute;
		left:78%;
		top:-10px
	}
	li{
		list-style: none;
		margin-left:30px;
		float: left;
		font-weight: bold;
		line-height: 80px;
	}
	a{
		color:lightgray;
		text-decoration: none;
		font-size: 25px;
			
	}
	a:hover{
		color:#fff;
		font-size: 30px;
	}
	span{
		color:#c8d3d3;
		font-size: 20px;
		position: absolute;
		top:35px;
		margin-left:20px;
		font-weight: bold;
	}

</style>