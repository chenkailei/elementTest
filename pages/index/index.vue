<template>
	<page-meta background-color="#00aaff">
		<navigation-bar title=""/>
	</page-meta>
	<view class="containerIndex">
		<uni-nav-bar left-text="饿了么" backgroundColor="#00aaff" color="#fff" height="60px" class="uni_nav_bar w100" :border="false"></uni-nav-bar>
		<view class=" container h100">
			<uni-row>
				<uni-col :span="12">
					<view class="ellipsis ft12">
						<uni-icons class="iconfont icon-weizhi"></uni-icons>
						<text>北京市西城区德胜街道普天德胜大厦</text>
					</view>
				</uni-col>
				<uni-col :span="12">
					<view class="ft8 fr lh17">
						<text>美食果蔬医药·30分钟送达</text>
					</view>
				</uni-col>
			</uni-row>
			
			<view class="search-bar mt10 pr">
				<input type="text" value="" class="searchInput ft12" placeholder="满记甜品"></input>
				<uni-icons class="iconfont icon-search ps ft12"></uni-icons>
				<button class="ps searchBtn ft12">搜索</button>
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
		methods: {

		}
	}
</script>

<style lang="scss">
	.containerIndex{
		height: 100%;
		background-color: '#00aaff';
		padding-top: 60px;
		.uni_nav_bar{
			position: fixed;
			top: 0;
			.uni-navbar-btn-text{
				margin-top: 28px;
				text{
					font-size: 16px!important;
				}
			}
		}
		.container{
			background-color: #eef;
			border-top-left-radius: 15px;
			border-top-right-radius: 15px;
			padding: 5px;
		}
		.icon-search{
			left: 4px;
			top: 4px;
			
		}
		.searchBtn{
			width: 15%;
			padding: 0 5px;
			right: 0px;
			top: 0px;
			height: 24px;
			line-height: 24px;
			background-color: #00aaff;
			color: #fff;
			border-radius: 15px;
		}
	}
</style>
