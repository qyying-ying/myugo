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
	<view class="swiper-box">
		<!-- 加冒号 后面的true才是布尔值 不加冒号是字符串 -->
        <swiper :indicator-dots="true" :autoplay="true" indicator-color="rgba(255,255,255,0.8)">
			<swiper-item>
				<navigator>
				    <image src="../../static/uploads/banner1.png">
			    </navigator>
			</swiper-item>
			<swiper-item>
				<navigator>
				    <image src="../../static/uploads/banner2.png">
			    </navigator>
			</swiper-item>
			<swiper-item>
				<navigator>
				    <image src="../../static/uploads/banner3.png">
			    </navigator>
			</swiper-item>
		</swiper>
	</view>
</view>
</template>

<script>
	export default {
		
	}
</script>

<style lang="less" scoped>
// 搜索
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
.swiper-box {
	swiper {
		height: 340rpx;
	}
	navigator {
		width: 750rpx;
		height: 340rpx;
	}
	image {
	   width: 100%;
	   height: 100%;
	}
}


</style>