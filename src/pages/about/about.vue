<template>
	<view class="about test-background">
		<text>uni-app小程序</text>
		<button @click="toNative">跳转到原生</button>
	</view>
</template>
<script>

	export default {
		components: {
		},
		data() {
			return {
			}
		},
		onLoad() {

		},
		methods: {
		    toNative () {
		        uni.navigateTo({
					url: '/pages/index/index'
				})
			}
		}
	}
</script>

<style lang="scss" scoped>
.about{
	text-align: center;
	line-height: 300rpx;
	font-size: 100rpx;
}
</style>
