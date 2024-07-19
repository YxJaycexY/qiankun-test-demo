<template>
  <div class="home">
    this is test
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Test',
  data() {
    return {
      isQiankun: window.__POWERED_BY_QIANKUN__,
    }
  },
  mounted() {
    console.log('app-vue-hash test.vue mounted')
    this.$router.push('/about')
  },
}
</script>
