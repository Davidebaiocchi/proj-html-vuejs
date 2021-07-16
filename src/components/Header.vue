<template>
  <header>
    <div class="upper-section">

      <div class="left">
        <i class="fas fa-clock blue-hover"> Open Hours: Mon - Sat - 9:00 - 18:00</i>
      </div>

      <div class="right">
        <i class="fas fa-phone-alt blue-hover"> +1 (123) 123-4568</i>
        <i class="fas fa-envelope blue-hover"> dado@gmail.com</i>
        <i class="fab fa-facebook-f blue-hover"></i>
        <i class="fab fa-twitter blue-hover"></i>
        <i class="fab fa-linkedin-in blue-hover"></i>
      </div>
    </div>

    <div class="lower-section">
      <div class="title">
        <span class="title-mod">Nex</span>
        <span>Gen</span>
      </div>

      <div class="navbar">
        <ul>
          <li class="blue-hover" v-for="(elementi, i) in menuHeader" :key="i" >
            {{ elementi }}
          </li>
          <li><button>get it touch</button></li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  
  data() {
    return {
      menuHeader : [
        'home',
        'about',
        'services',
        'process',
        'team',
        'blog',
      ]
    }
      
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

  @import '@/style/1upperHeader.scss';
  @import '@/style/2lowerHeader.scss';

</style>
