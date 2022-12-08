<template>
	<view class="card">
		- {{title}} -
	</view>
</template>

<script>
	export default {
		name:"Card",
		props:{
			title:String,
		},
		data() {
			return {
				
			};
		}
	}
</script>

<style scoped>
.card{
	padding: 20px 0;
	text-align: center;
	font-weight: bold;
}
</style>