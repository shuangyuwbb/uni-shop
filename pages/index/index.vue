<template>
	<view class="container">
		<uni-search-bar placeholder="自定placeholder" @confirm="search"></uni-search-bar>
		<view class="intro"></view>
		<text class="intro"></text>
		<uni-link :href="href" :text="href"></uni-link>
	</view>
</template>

<script>
	import uniSearchBar from '@/components/uni-search-bar/uni-search-bar.vue'
	export default {
		data() {
			return {
				href: 'https://uniapp.dcloud.io/component/README?id=uniui'
			}
		},
		components:{
			uniSearchBar
		},
		methods: {

		}
	}
</script>

<style lang="scss">
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
