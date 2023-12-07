<template>
	<view>
		<audio loop="true" 
		controls="true" 
		src="https://bjetxgzv.cdn.bspapp.com/VKCEYUGU-hello-uniapp/2cc220e0-c27a-11ea-9dfb-6da8e309e0d8.mp3"
		 @play="play"
		 @pause="pause"></audio>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			play(e)
			{
				console.log(e);
				console.log("开始/继续播放");
			},
			pause(e)
			{
				console.log("暂停播放");
			}
		}
	}
</script>

<style>

</style>
