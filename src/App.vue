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
