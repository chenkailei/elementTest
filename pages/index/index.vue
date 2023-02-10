<template>
	<page-meta background-color="#00aaff">
		<navigation-bar title=""/>
	</page-meta>
	<view class="containerIndex">
		<uni-nav-bar left-text="饿了么" backgroundColor="#00aaff" color="#fff" height="60px" class="uni_nav_bar w100" :border="false"></uni-nav-bar>
		<view class=" container h100">
			<uni-row>
				<uni-col :span="12">
					<view>
						<uni-icons class="iconfont icon-weizhi"></uni-icons>
						<text class="uni-ellipsis-1">北京市西城区德胜街道普天德胜大厦</text>
					</view>
				</uni-col>
				<uni-col :span="12">
					<view class="">2</view>
				</uni-col>
			</uni-row>
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
		}
	}
</style>
