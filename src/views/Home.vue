<template>
  <div id="Home" class="Home">
	<img src="../../src/assets/logo.jpg"/>
</div>
</template>

<script>
export default {
	el: '#Home',
	data(){
		return {
			title: 'Home'
		}
	}
}
</script>

<style scoped>
/* Template CSS (You can delete all of this :) */

body {
	background: rgb(17,17,17);
	background: linear-gradient(45deg, rgba(17,17,17,1) 50%, rgba(33,33,33,1) 100%);  
	color: #fff;
	display: flex;
	justify-content: center;
	align-items: center;
}
.Home {
	display: flex;
	flex-direction: column;
	text-align: center;
}
.Home h1 {
	font-size: 2rem;
	font-weight: 700;
	color: #4dba87;
}
.Home img {
  margin-top: 10%;
  width: 100%;
  height: 100%;
}
</style>