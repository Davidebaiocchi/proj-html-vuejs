<template>
  <main>
    <MainAJumbotron/>
    <MainBSliderDark/>
    <MainCSliderlight/>
  </main>
</template>

<script>
import MainAJumbotron from '@/components/MainAJumbotron.vue'
import MainBSliderDark from '@/components/MainBSliderDark.vue'
import MainCSliderlight from '@/components/MainCSliderlight.vue'

export default {
  name: 'Main',
  components: {
      MainAJumbotron,
      MainBSliderDark,
      MainCSliderlight,
  }
  
}
</script>

<style scoped lang="scss">
  
</style>
