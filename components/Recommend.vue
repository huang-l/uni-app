<template>
	<view class="recommand">
		<view class="recommand-item">
			<image class="item-big" src="../static/tabbar/index.svg"></image>
			<view class="item-small">
				<image class="item" src="../static/tabbar/list.svg"></image>
				<image class="item" src="../static/tabbar/shopcart.svg"></image>
				<image class="item" src="../static/tabbar/my.svg"></image>
			</view>
		</view>
		<view class="recommand-item">
			<image class="item-big" src="../static/tabbar/index.svg"></image>
			<view class="item-small">
				<image class="item" src="../static/tabbar/list.svg"></image>
				<image class="item" src="../static/tabbar/shopcart.svg"></image>
				<image class="item" src="../static/tabbar/my.svg"></image>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		name: "Recommend",
		data() {
			return {

			};
		}
	}
</script>

<style lang="scss" scoped>
	.recommand {
		background: #1890ff;
		padding: 10px;
		.recommand-item {
			margin-bottom: 10px;
			background: #fff;
			border-radius: 10px;
			height: 240px;
			.item-big {
				width: 100%;
				height: 120px;
			}
			.item-small {
				height: 120px;
				.item {
					width: 33.33%;
					height: 100%;
				}
			}
		}
	}
</style>
