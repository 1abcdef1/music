<template>
    <div class='m-header'>
          网易云音乐
    </div>
    
</template>
<script>

export default {
    name:'MHeader'
}
</script>
<style lang="less">
  @import '~style/index.less';
  .m-header{
  	.bug(red);
      .w(375);
      .h(60);
      text-align: left;
      .l_h(60);
      color:#fff;
      background:#d43c33;
      font-size: @font-size-ms;
  }  
</style>