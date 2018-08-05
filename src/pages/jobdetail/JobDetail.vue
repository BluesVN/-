<template>
<div>
  <detail-header></detail-header>
  <div class="detail-box">
    <detail-left></detail-left>
    <detail-middle></detail-middle>
  </div>
</div>
</template>
<script>

import DetailHeader from './components/Header'
import DetailLeft from './components/DetailLeft'
import DetailMiddle from './components/DetailMiddle'

// import axios from 'axios'
export default {
  name: 'JobDetail',
  components: {
    DetailHeader,
    DetailLeft,
    DetailMiddle
  },
  data () {
    return {

    }
  }
}
</script>
<style lang="stylus" scoped>
  .detail-box
    display flex
</style>
