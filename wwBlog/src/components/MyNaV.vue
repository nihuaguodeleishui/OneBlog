<template>
	<div class="nav-all">
		<div class="tx"></div>
		<div class="nav-dh">
			<h3>知名博主</h3>
			<span class="dh1">
				文章
			</span>
			<span class="dh2">
				分类
			</span>
		</div>
	</div>
</template>

<script>
</script>

<style>
	.nav-all{
		border:3px solid #fff;
		border-radius: 25px;
		width: 200px;
		height: 400px;
		position: absolute;
		left: 310px;
		top:200px;
		background: #175391;
		opacity: 0.8;
	}
	.tx{
		width: 120px;
		height: 120px;
		border:1px solid #fff;
		border-radius: 50%;
		position: relative;
		left:40px;
		top:15px;
		background-image: url(../assets/dog.jpg);
		background-size: 100% 100%;
		background-repeat: no-repeat;
	
	}
	h3{
		color:white;
		position: relative;
		left:60px;
		top:25px
	}
	.dh1{
		color:white;
		font-size: 18px;
		font-weight: bold;
		position: relative;
		left:20px;
		top:75px
	}
	.dh2{
		color:white;
		font-size: 18px;
		font-weight: bold;
		position: relative;
		left:40px;
		top:75px
	}
</style>