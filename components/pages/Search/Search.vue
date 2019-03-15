<template>
<div class="wrapper wrapper-Search">
		<div class="content">
			
		</div>
		<router-view></router-view>
	</div>
</template>
<script>
export default {
    
}
</script>
<style lang="less" scope>
	@import '~style/index.less';
    .wrapper-Search{
		/*.bug(red);*/
		background: #fff;
		position:fixed;
		overflow:hidden;
		.top(100);
		.bottom(0);
		.w(375);
		color:#222;
	}
</style>