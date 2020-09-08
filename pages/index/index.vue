<template>
	<view class="content">
		<!-- 轮播图部分 -->
		<swiper :indicator-dots="true" :autoplay="true" autoplay circular>
			
			<swiper-item>
				<view class="swiper-item">
					<image src="../../static/bz.png" mode=""></image>
				</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item">
					<image src="../../static/bz.png" mode=""></image>
				</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item">
					<image src="../../static/bz.png" mode=""></image>
				</view>
			</swiper-item>
		</swiper>
		<!-- 图标区 -->
		<view class="icon">
			<view class="icon-item">
				<view class="iconfont icon-shipin"></view>
				<text>视频</text>
			</view>
			<view class="icon-item">
				<view class="iconfont icon-ziyuan"></view>
				<text>商品</text>
			</view>
			<view class="icon-item">
				<view class="iconfont icon-tupian"></view>
				<text>图片</text>
			</view>
			<view class="icon-item">
				<view class="iconfont icon-guanyuwomen"></view>
				<text>关于我们</text>
			</view>
		</view>
		<!-- 商品区 -->
		<view class="card">
			<view class="title">
				推荐商品
			</view>
			<view class="goods">
				<view class="goods-item">
					<view class="img">
						<image src="../../static/bz.png" mode=""></image>
					</view>
					<view class="price">
						<text>￥1799</text>
						<text>￥1999</text>
					</view>
					<view class="goods-info">
						乏味奥斯卡静安里打开那啥快递件爱丽丝的女生
					</view>
				</view>
				<view class="goods-item">
					<view class="img">
						<image src="../../static/bz.png" mode=""></image>
					</view>
					<view class="price">
						<text>￥1799</text>
						<text>￥1999</text>
					</view>
					<view class="goods-info">
						乏味奥斯卡静安里打开那啥快递件爱丽丝的女生， 按实际大理石侃大山
					</view>
				</view>
				<view class="goods-item">
					<view class="img">
						<image src="../../static/bz.png" mode=""></image>
					</view>
					<view class="price">
						<text>￥1799</text>
						<text>￥1999</text>
					</view>
					<view class="goods-info">
						乏味奥斯卡静安里打开那啥快递件爱丽丝的女生
					</view>
				</view>
				<view class="goods-item">
					<view class="img">
						<image src="../../static/bz.png" mode=""></image>
					</view>
					<view class="price">
						<text>￥1799</text>
						<text>￥1999</text>
					</view>
					<view class="goods-info">
						乏味奥斯卡静安里打开那啥快递件爱丽丝的女生
					</view>
				</view>
				<view class="goods-item">
					<view class="img">
						<image src="../../static/bz.png" mode=""></image>
					</view>
					<view class="price">
						<text>￥1799</text>
						<text>￥1999</text>
					</view>
					<view class="goods-info">
						乏味奥斯卡静安里打开那啥快递件爱丽丝的女生
					</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang="scss">
	
	.content{
		width:750rpx;
		swiper{
			height:320rpx;
			width:750rpx;
			image{
				width:100%;
				height:320rpx;
			}
		}
		.icon{
			margin-top:10rpx;
			display: flex;
			.icon-item{
				width:25%;
				// border:1px solid red;
				height:160rpx;
				// box-sizing: border-box;
				text-align: center;
				view{
					// margin:0 auto;
					width:100rpx;
					height: 100rpx;
					border-radius: 50rpx;
					background-color: $font-color;
					margin:0 auto;
					line-height: 100rpx;
					font-size:44rpx;
					color: #fff;
					margin-bottom: 8rpx;
				}
				text{
					// text-align: center;
					letter-spacing: 4rpx;
				}
			}
		}
		.card{
			wdith:750rpx;
			background: #ecebe7;
			// border:1px solid red;
			padding-top:8rpx;
			.title{
				// height: 70rpx;
				line-height:100rpx;
				background-color: #ffffff;
				color:$font-color;
				text-align: center;
				letter-spacing: 10rpx;
				font-size:38rpx;
				padding-bottom: 10rpx;
			}
		}
		.goods{
			margin-top:10rpx;
			background-color: #ecebe7;
			display: flex;
			flex-wrap: wrap;
			justify-content: space-between;
			.goods-item{
				background-color: #FFFffF;
				width:354rpx;
				padding:10rpx 5rpx;
				margin:4rpx 4rpx;
				.img{
					width: 80%;
					height: auto;
					display: block;
					margin:0 auto;
					image{
						width: 100%;
					}
				}
				.price{
					 font-size: 38rpx;
					 padding:10rpx;
					 color: $font-color;
					 text:nth-of-type(2){
						 color:#aaaaaa;
						 margin-left:12rpx ;
						 font-size: 30rpx;
						 text-decoration: line-through;
					 }
				}
				.goods-info{
					line-height: 40rpx;
					padding:0 10rpx;
					letter-spacing: 4rpx;
					font-size: 36rpx;
				}
			}
		}
	}
	
</style>
