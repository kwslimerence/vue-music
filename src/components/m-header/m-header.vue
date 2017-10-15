<template>
   <div class="m-header">
     <div class="icon"></div>
     <h1 class="text">舒先生，你好</h1>
   </div>
</template>

<script>
  export default {

  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  @import '~common/stylus/variable'
  @import '~common/stylus/mixin'

   .m-header
    height:44px
    text-align:center
    color:$color-theme
    font-size:0
    .icon
     display:inline-block
     width:32px
     height:30px
     margin-top:6px
     margin-right:9px
     vertical-align:top
     bg-image:('logo')
     background-size:30px 32px
    .text
     display:inline-block
     vertical-align:top
     line-height:44px
     font-size:$font-size-large
</style>
