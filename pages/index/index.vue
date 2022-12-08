<template>
	<view class="content">
		<IndexSwiper/>
		<Recommend/>
		<Card title="猜你喜欢"/>
		<view class="iconfont icon-xiaoxi"></view>
	</view>
</template>

<script>
	import IndexSwiper from '@/components/IndexSwiper.vue'
	import Recommend from '@/components/Recommend.vue'
	import Card from '@/components/Card.vue'
	export default {
		components:{IndexSwiper,Recommend,Card},
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
</style>
