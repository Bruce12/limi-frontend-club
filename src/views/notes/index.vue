<template>
  <div class="home">
    笔记列表
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'
@Options({
  components: {}
})
export default class Home extends Vue {
}
</script>
<style lang="less" scoped>
  .home {
    height: 100vh;
  }
</style>
