<template>
	<swiper class="swiper" :indicator-dots="true" :autoplay="true" :duration="1000" :interval="3000">
		<swiper-item>
			<image class="swiper-img" src="../static/tabbar/my.svg"></image>
		</swiper-item>
		<swiper-item>
			<image class="swiper-img" src="../static/tabbar/shopcart.svg"></image>
		</swiper-item>
		<swiper-item>
			<image class="swiper-img" src="../static/tabbar/list.svg"></image>
		</swiper-item>
	</swiper>
</template>

<script>
	export default {
		name: "IndexSwiper",
		data() {
			return {

			};
		}
	}
</script>

<style scoped>
	.swiper {
		width: 100%;
		height: 200px;
	}

	.swiper-img {
		width: 100%;
		height: 100%;
	}
</style>
