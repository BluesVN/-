<template>
  <div class="detail-left">
    <div class="city">
      <span>地区</span>
      <button>武汉</button>
    </div>
    <ul class="list">
      <li class="select">热门</li>
      <li>推荐</li>
    </ul>
  </div>
</template>
<script>
export default {
  name: 'DetailLeft'
}
</script>
<style lang="stylus" scoped>
@import '~styles/variables'
  .detail-left
    xbackground-color red
    margin-left  $leftOffset
    min-width 1.5rem
    .city
      padding .18rem 0
    .city button
      background-color $mainBlue
      padding 0.02rem .05rem
      font-size .14rem
      color #fff
    .list
      font-size .2rem
      text-align center
    .list li
      padding .14rem 0
    .select
      background-color $logoColor
      color #fff
</style>
