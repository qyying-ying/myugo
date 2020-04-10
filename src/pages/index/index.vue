<template>
	<view class="content">
		<image class="logo" src="/static/logo.png"></image>
		<view>
			<text class="title">{{title}}</text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		// 页面生命周期
		onLoad() {
			// 执行第一次
          console.log('onload首页 刚刚加载')
		},
		onShow() {
          console.log('onshow首页 显示')
		},
		onReady() {
			// 执行第一次
          console.log('onReady首页 初次渲染')
		},
		onHide() {
          console.log('onHide首页 隐藏')
		},
		onUnload() {
			console.log('onUnload首页 被卸载')
		},
		methods: {

		}
	}
</script>

<style>
	.content {
		text-align: center;
		height: 400upx;
	}

	.logo {
		height: 200upx;
		width: 200upx;
		margin-top: 200upx;
	}

	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
</style>
