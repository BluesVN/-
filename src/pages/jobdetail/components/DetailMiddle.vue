<template>
  <div>
    <ul class="tab border-bottom">
      <li class="click">综合</li>
      <li>平均工资</li>
      <li>需求量</li>
      <li>职位类别</li>
    </ul>
    <ul class="list">
      <li class="li border-bottom">
        <span class="li-left"></span>
        <div class="li-middle">
          <h3>首席财务官CFO</h3>
          <span class="middle-text">三年平均薪资</span>
          <span class="text-s">一线10000<span class="vs">VS</span>本地10000</span>
        </div>
        <div class="li-right">
          <span class="right-text">需求量(人)</span>
          <span class="text-s">一线10000<span class="vs">VS</span>本地10000</span>
        </div>
      </li>
      <li class="li border-bottom">
        <span class="li-left"></span>
        <div class="li-middle">
          <h3>首席财务官CFO</h3>
          <span class="middle-text">三年平均薪资</span>
          <span class="text-s">一线10000<span class="vs">VS</span>本地10000</span>
        </div>
        <div class="li-right">
          <span class="right-text">需求量(人)</span>
          <span class="text-s">一线10000<span class="vs">VS</span>本地10000</span>
        </div>
      </li>
      <li class="li border-bottom">
        <span class="li-left"></span>
        <div class="li-middle">
          <h3>首席财务官CFO</h3>
          <span class="middle-text">三年平均薪资</span>
          <span class="text-s">一线10000<span class="vs">VS</span>本地10000</span>
        </div>
        <div class="li-right">
          <span class="right-text">需求量(人)</span>
          <span class="text-s">一线10000<span class="vs">VS</span>本地10000</span>
        </div>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: 'DetailMiddle'
}
</script>
<style lang="stylus" scoped>
@import '~styles/variables'

.tab
  display: flex
  justify-content: flex-start
  align-content: center
  min-width: 9.6rem
  margin-left: 0.2rem
  padding: 0.18rem 0

.tab li
  margin-left: 0.5rem

.click
  color: $mainBlue

.li
  display: flex
  justify-content: start
  padding .3rem .7rem
  .li-left
    background-color: red
    width: 0.5rem
    height: 0.5rem

  .li-middle
    display: flex
    flex-direction: column
    margin 0 1rem 0 .25rem
    .middle-text
      font-size .23rem
      margin .2rem 0 .15rem 0
  .li-right
    display: flex
    flex-direction: column
    justify-content: flex-end
    .right-text
      font-size .24rem
      margin .2rem 0 .15rem 0
  .text-s
    font-size .2rem
  .vs
    font-size .25rem
    color $mainBlue
    margin 0 .06rem
</style>
