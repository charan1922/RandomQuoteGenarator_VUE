<template>
	<div id="app">
		<img width=150 src="./assets/logo.png">
		<router-view></router-view>
	</div>
</template>


<script>
	export default {
    name: 'app'
  }
</script>

<style>
	#app {
 background-image: url('https://res.cloudinary.com/dgmilxzy7/image/upload/c_scale,w_500,o_75,b_rgb:07beb8/v1506735375/CodePen/ViddenPixel.jpg');
    background-position: center;
    background-size: cover;
    height: 44rem;


	//	background:  linear-gradient(to bottom, #68d8d6 ,#ffffff );
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
	}
</style>