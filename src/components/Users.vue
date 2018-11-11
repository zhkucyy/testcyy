<template>
  <div class="users">
  	<h1>Hello users</h1>
       <ul>
       		<li v-for="user in users">
       			{{user}}
       		</li>
       </ul>
  </div>
</template>

<script>
export default {
  name: 'users',
  data () {
    return {
      users:["Henry","Bucky","Emily"]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
	color: green;
}
*{}
</style>


<!--
	作者：1103886401@qq.com
	时间：2018-11-08
	描述：
	
	scoped:当前组件样式可用
-->

