<template>
  <main>
    <MainAJumbotron/>
    <MainBSliderDark/>
  </main>
</template>

<script>
import MainAJumbotron from '@/components/MainAJumbotron.vue'
import MainBSliderDark from '@/components/MainBSliderDark.vue'

export default {
  name: 'Main',
  components: {
      MainAJumbotron,
      MainBSliderDark,
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
