<template>
<div>
  <detail-header></detail-header>
  <detail-left></detail-left>
</div>
</template>
<script>

import DetailHeader from './components/Header'
import DetailLeft from './components/DetailLeft'

// import axios from 'axios'
export default {
  name: 'JobDetail',
  components: {
    DetailHeader,
    DetailLeft
  },
  data () {
    return {

    }
  }
}
</script>
<style lang="stylus" scoped>

</style>
