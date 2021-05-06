<template>
  <div>
    <h3 class="title">{{ msg }}</h3>
    <el-row>
      <search :visible="visible"></search>
    </el-row>
  </div>
</template>

<script>
import Search from './Search'

export default {
  components: {
    Search
  },
  data () {
    return {
      msg: 'vue-amap-starter',
      visible: true
    }
  }
}
</script>

<style>
</style>
