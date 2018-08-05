<template>
<div class="wrapper">
  <div class="swiper-pagination"  slot="pagination"></div>
  <div class="title">热榜</div>

  <swiper :options="swiperOption">

    <swiper-slide class="slide">
      <div>
        <div class="item">
          <div class="item-h"></div>
          <div class="item-name">昵称
            <p class="date">2018-06-26</p>
          </div>
          <img src="../../../assets/image/attention.png" alt="">
        </div>
        <ul class="slide-list">
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
        </ul>
      </div>
      <div>
        <div class="item">
          <div class="item-h"></div>
          <div class="item-name">昵称
            <p class="date">2018-06-26</p>
          </div>
          <img src="../../../assets/image/attention.png" alt="">
        </div>
        <ul class="slide-list">
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
        </ul>
      </div>
      <div>
        <div class="item">
          <div class="item-h"></div>
          <div class="item-name">昵称
            <p class="date">2018-06-26</p>
          </div>
          <img src="../../../assets/image/attention.png" alt="">
        </div>
        <ul class="slide-list">
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
        </ul>
      </div>

    </swiper-slide>
    <swiper-slide class="slide">
      <div>
        <div class="item">
          <div class="item-h"></div>
          <div class="item-name">昵称
            <p class="date">2018-06-26</p>
          </div>
          <img src="../../../assets/image/attention.png" alt="">
        </div>
        <ul class="slide-list">
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
        </ul>
      </div>
      <div>
        <div class="item">
          <div class="item-h"></div>
          <div class="item-name">昵称
            <p class="date">2018-06-26</p>
          </div>
          <img src="../../../assets/image/attention.png" alt="">
        </div>
        <ul class="slide-list">
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
        </ul>
      </div>
      <div>
        <div class="item">
          <div class="item-h"></div>
          <div class="item-name">昵称
            <p class="date">2018-06-26</p>
          </div>
          <img src="../../../assets/image/attention.png" alt="">
        </div>
        <ul class="slide-list">
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
        </ul>
      </div>

    </swiper-slide>
    <swiper-slide class="slide">
      <div>
        <div class="item">
          <div class="item-h"></div>
          <div class="item-name">昵称
            <p class="date">2018-06-26</p>
          </div>
          <img src="../../../assets/image/attention.png" alt="">
        </div>
        <ul class="slide-list">
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
        </ul>
      </div>
      <div>
        <div class="item">
          <div class="item-h"></div>
          <div class="item-name">昵称
            <p class="date">2018-06-26</p>
          </div>
          <img src="../../../assets/image/attention.png" alt="">
        </div>
        <ul class="slide-list">
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
        </ul>
      </div>
      <div>
        <div class="item">
          <div class="item-h"></div>
          <div class="item-name">昵称
            <p class="date">2018-06-26</p>
          </div>
          <img src="../../../assets/image/attention.png" alt="">
        </div>
        <ul class="slide-list">
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
          <li class="border-bottom">
            <p class="li-title">销售/客服/市场</p>
            <img class="li-img" src="../../../assets/image/right_hot.png">
          </li>
        </ul>
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
    background-color: #fff

    .item
      display: flex
      flex-direction: row
      white-space: nowrap
      margin-bottom: 1px
      justify-content: space-around
      align-content: center
      align-items: center
      background: #fff
      padding: 0.15rem 0

      .item-h
        width: 0.5rem
        height: 0.5rem
        background: red
        border-radius: 100%

      .item-name
        font-size: 0.2rem
        margin-left: -0.4rem

        .date
          font-size: 0.07rem
          color: #aaa
          margin-top: 0.05rem

    .slide-list
      padding: 0.15rem
      .li-title
        font-size .18rem
        margin-bottom .15rem
      .li-img
        width 100%
        margin-bottom .28rem

</style>
