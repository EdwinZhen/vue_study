<template>
	<div>
		test专用
	</div>
</template>
<script>
	export default {
		components: {
			'my-btn' : MyBtn
		},
		data: function () {
			return {
				test2: '测试数据'
			}
		},
		methods: {
			testfunc: function () {
				console.log('test666')
			}	
		}
	};
	
</script>
<style>
	
</style>