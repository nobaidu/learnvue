<template>
	<div class="banner">
		<img class="logo" src="../assets/images/logo.jpg" alt="logo">
		<van-swipe :autoplay="5000" indicator-color="white">
			<van-swipe-item v-for="(image , index) in images" :key="index">
				    <img v-lazy="image" alt="banner" width="100%" height="auto"/>
			</van-swipe-item>
		</van-swipe>
	</div>
</template>

<script>
export default {
  data(){
	  return{
		  images:[
			require('../assets/images/banner1.jpg'),
			require('../assets/images/banner2.jpg'),
			require('../assets/images/banner3.jpg'),
			require('../assets/images/banner4.jpg'),
		  ]
	  }
  },
  methods:{
	  
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	.banner{
		position: relative;
		overflow: hidden;
	}
	.logo{
		position: absolute;
		top: 0;
		left: 0;
		z-index: 100;
		width: 120px;
	}
</style>
