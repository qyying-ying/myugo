<template>
<view class="index">
		<!-- search搜索 -->
	<view class="search">
		<!-- 搜索框 -->
		<view class="search-input">
            <input type="text" placeholder="请搜索您要的商品">
		</view>
        <!-- 搜索结果内容 -->
	    <view class="search-content"></view>
	</view>
	<!-- 轮播图 -->
</view>
</template>

<script>
	export default {
		
	}
</script>

<style lang="less" scoped>
.search {
  .search-input {
   padding: 18rpx;
   background-color: #ea4451;
  }
  input {
	background-color: #fff;
	height: 60rpx;
	padding-left: 15rpx;
	font-size: 26rpx;
	color: #eee;
   }

}


</style>