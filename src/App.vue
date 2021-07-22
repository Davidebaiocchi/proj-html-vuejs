<template>
  <div id="app">
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&family=Prata&display=swap');

  * {
    box-sizing: border-box;
    margin: 0;
    border: 0;
  }

  // tag generale per l' hover di colore azzurro
  .blue-hover:hover {
    color: rgb(19, 158, 158);
    cursor: pointer;
    scale: 1.1;
  }

  
</style>
