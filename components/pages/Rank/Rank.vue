<template>
<div class="rank" ref='wrapper'>
    <div class="content">
        <div class="rankImg">
        	
        </div>
        <div class="rankList">
        	<ul>
        		<li></li>
        	</ul>
        </div>
    </div>
</div>
</template>
<script>
import BScroll from 'better-scroll'
export default {
	data() {
		return {
			rankList: []
		}
	},
	created:{
		
	}
}
</script>
<style lang="less" scope>@import '~style/index.less';
.rank {
	.w(375);
	.h(580);
	.top(100);
	.left(0);
	.bottom(0);
	.right(0);
	.bug(red);
	background: #fff;
	overflow: hidden;
	.content {
		.rankImg{
			.w(375);
			.h(146);
			background: red;
		}
		.rankList{
			
		}
	}
}
</style>