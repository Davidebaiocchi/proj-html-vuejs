<template>
  <main>
    <MainAJumbotron/>
    <MainBSliderDark/>
    <MainCSliderlight/>
    <MainDProcessManagement/>
    <MainETeamExpert/>
    <MainFNews/>
    <MainGNewsLetter/>

  </main>
</template>

<script>
import MainAJumbotron from '@/components/MainAJumbotron.vue'
import MainBSliderDark from '@/components/MainBSliderDark.vue'
import MainCSliderlight from '@/components/MainCSliderlight.vue'
import MainDProcessManagement from '@/components/MainDProcessManagement.vue'
import MainETeamExpert from '@/components/MainETeamExpert.vue'
import MainFNews from '@/components/MainFNews.vue'
import MainGNewsLetter from '@/components/MainGNewsLetter.vue'

export default {
  name: 'Main',
  components: {
      MainAJumbotron,
      MainBSliderDark,
      MainCSliderlight,
      MainDProcessManagement,
      MainETeamExpert,
      MainFNews,
      MainGNewsLetter,
  }
  
}
</script>

<style scoped lang="scss">
  
</style>
