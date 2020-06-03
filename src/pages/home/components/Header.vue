<template>
  <div class="header">
    <div class="header-left">返回</div>
    <div class="herder-input">输入城市/景点/游玩主题</div>
    <div class="herder-right">城市</div>
  </div>
</template>

<script>

export default {
  name: 'HomeHeader'

}
</script>

// 1 rem = html font-size = 50px
<style lang="stylus" scoped>
  .header
    display flex
    height: .86rem
    background #00bcd4
    color #fff
    line-height .86rem
    .herder-left
      width: .64rem
      float left
    .herder-input
      flex 1
      // 用到lineheight的化，要定死
      height 64rem
      line-height .64rem
      height .64rem
      margin-top .12rem
      margin-left .2rem
      background-color #fff
      border-radius .1rem
      color #ccc
    .herder-right
      width 1.24rem
      float right

</style>
