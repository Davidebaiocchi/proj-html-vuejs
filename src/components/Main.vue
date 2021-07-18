<template>
  <main>
    <MainAJumbotron/>
    <MainBSliderDark/>
    <MainCSliderlight/>
    <MainDProcessManagement/>
  </main>
</template>

<script>
import MainAJumbotron from '@/components/MainAJumbotron.vue'
import MainBSliderDark from '@/components/MainBSliderDark.vue'
import MainCSliderlight from '@/components/MainCSliderlight.vue'
import MainDProcessManagement from '@/components/MainDProcessManagement.vue'

export default {
  name: 'Main',
  components: {
      MainAJumbotron,
      MainBSliderDark,
      MainCSliderlight,
      MainDProcessManagement,
  }
  
}
</script>

<style scoped lang="scss">
  
</style>
