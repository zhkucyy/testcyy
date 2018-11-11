<template>
	<div class="login">
		<h1>{{msg}}</h1>
		<div class="row">
			<label for="username"><span class="right"><span class="red">{{icon}}</span>{{username}}</span></label>
			<input type="text" name="username" id="username" />
			<span id="error1"></span>
		</div>
		<div class="row">
			<label for="password"><span class="right"><span class="red">{{icon}}</span>{{password}}</span></label>
			<input type="text" name="password" id="password" />
			<span id="error1"></span>
		</div>
		<div class="row">
			<span class="right"><span class="red"></span></span>
			<button>登录</button>
		</div>
	</div>
</template>

<script>
	export default {
		name: 'login',
		data() {
			return {
				msg: "登录",
				icon: "*",
				username: "用户名：",
				password: "密码："
			}
		}
	}
</script>

<style>
	h1 {
		color: purple;
		text-align: center;
	}
	
	.row {
		margin-top: 10px;
	}
	
	.right {
		width: 150px;
		text-align: right;
		display: inline-block;
	}
	
	.red {
		color: red;
	}
</style>