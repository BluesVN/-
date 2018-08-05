<template>
<div class="wrapper">
  <div class="swiper-pagination"  slot="pagination"></div>
  <div class="title">网络红人</div>

  <swiper :options="swiperOption">

    <swiper-slide class="slide">
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
    </swiper-slide>
    <swiper-slide class="slide">
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
    </swiper-slide>
    <swiper-slide class="slide">
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
      <div class="item">
        <div class="item-h"></div>
        <div class="item-name">昵称</div>
        <img src="../../../assets/image/attention.png" alt="">
      </div>
    </swiper-slide>

  </swiper>
</div>
</template>
<script>
export default {
  name: 'SwiperPoP',
  props: {},
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        loop: true
      }
    }
  },
  computed: {}
}
</script>
<style lang="stylus" scoped>
@import '~styles/variables'

.wrapper >>> .swiper-pagination
  margin-left: 2.6rem
  margin-top: -0.12rem

.wrapper >>> .swiper-pagination-bullet
  background-color: #fff !important
  border-radius: 0
  width: 0.1rem
  height: 0.1rem

.wrapper >>> .swiper-pagination-bullet-active
  background-color: $logoColor !important

.wrapper
  background-color: $mainBgc
  min-width: 1rem
  margin-top: 0.25rem
  padding: 0.15rem 0.2rem

  .title
    border-left: 0.04rem solid $logoColor
    font-size: 0.23rem
    padding-left: 0.07rem
    margin-bottom: 0.1rem

  .slide
    min-height: 4rem

    .item
      display: flex
      flex-direction: row
      white-space: nowrap
      margin-bottom: .01rem
      margin-left -.1rem
      justify-content: space-around
      align-content: center
      align-items: center
      background: #fff
      padding: 0.15rem 0

      .item-h
        width: 0.66rem
        height: 0.66rem
        background: red
        border-radius: 100%

      .item-name
        font-size: 0.2rem
        margin-left: -0.4rem;
</style>
