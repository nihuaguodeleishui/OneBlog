<template>
	<div class="login1">
		<h1>login</h1>
		<div class="user">Username:<input type="text" placeholder="username" id="use1"/></div>
		<br />
		<div class="psw">Password:<input type="password" placeholder="password" id="ps1"/></div>
		<button class="btn1" @click="btn01">登录</button>
		<button class="btn2">注册</button>
	</div>
</template>

<script>
	export default{
		methods:{
			btn01(){
				if(this.input===123 && this.input===234){
					alert("登陆成功")
				}else{
					alert("错误")
				}
			}
		}
	}
</script>

<style>
	body{
		background-image:linear-gradient(to top,#fad0c4 20%,#ffd1ff 80%);
	}
	/* 登陆界面 */
	.login1{
		position: absolute;
		left:50%;
		top:50%;  
		transform: translate(-50%, -50%);   
		width: 500px;
		height: 300px;
		border:1px solid #fff;
		clip-path: inset(0 round 10px);
		border-image: linear-gradient(#ddd,#000) 60 40;
	}
	/* 标题 */
	h1{
		text-align: center;
		color:gray;
	}
	/* 用户 */
	.user{
		width: 260px;
		height: 25px;
		position: relative;
		left:120px;
	}
	/* 密码 */
	.psw{
		width: 260px;
		height: 25px;
		position: relative;
		left:125px;
	}
	/* 文本框样式 */
	input{
		width:160px;
		height: 23px;
		border-radius: 15px;
		margin-left: 5px;
		border-color:#fad0c4;
	}
	.btn1{
		width: 100px;
		height: 40px;
		border-radius: 10px;
		background-color:#fad0c4 ;
		position: relative;
		left: 40%;
		top:20px;
		color:darkslategray;
	}
	.btn2{
		width: 60px;
		height: 30px;
		border-radius: 10px;
		background-color: #ffd1ff;
		position: relative;
		left: 24%;
		top:70px;
		color:dimgray;
	}
</style>