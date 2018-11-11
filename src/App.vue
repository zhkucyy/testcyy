<!-- 模板html结构 -->
<template>
	<div id="app">
		<div id="main">
			<!--<loginbackground></loginbackground>
			<login></login>-->
			<div class="container">
				<app-header> </app-header>
			</div>
		</div>
	</div>
</template>

<!-- 行为处理行为 -->
<script>
//	import login from './components/login'
//	import loginbackground from './components/loginbackground'
//
//	export default {
//		name: 'App',
//		data() {
//			return {
//
//			}
//		},
//		components: {
//			"login": login,
//			"loginbackground": loginbackground
//
//		}
//	}

import Header from './components/Header'

export default{
	components:{
		appHeader:Header
	}
}
</script>

<!-- 样式解决 -->
<style>
	/*#main {
		margin: 0 auto;
		width: 500px;
	}*/
</style>