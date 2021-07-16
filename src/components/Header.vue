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
  props: {
  },
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
  .upper-section {
    height: 50px;
    line-height: 50px;
    display: flex;
    justify-content: space-around;
    background: rgb(17,37,48);
    background: linear-gradient(90deg, rgba(17,37,48,1) 0%, rgb(12, 41, 58) 85%, rgb(34, 57, 71) 100%);
  }

  .left, .right {
    color: lightgrey;
  }

  i {
    margin-right: 20px;
  }

  // parte bassa header
  .lower-section {
    height: 70px;
    line-height: 70px;
    display: flex;
    justify-content: space-around;
  }

  .title {
    font-size: 22px;
    text-transform: uppercase;
    color: rgb(0, 0, 0);
    font-weight: 800;
  }

  .title-mod {
    background-color: rgba(12, 226, 197, 0.226);
    padding: 10px 0;
    padding-left: 20px;
    border-top-left-radius: 20px;
    border-bottom-left-radius: 20px;
    color: rgba(31, 102, 93, 0.692);
    margin-right: 3px;
  }
 
  li {
    display: inline-block;
    color: rgb(44, 44, 44);
    margin-right: 30px;
    font-size: 18px;
    text-transform: uppercase;
  }

  button {
    color: white;
    background-color: #048383;
    height: 40px;
    padding: 0 18px;
    text-transform: uppercase;
    font-size: 14px;
    font-weight: bolder;
    border-radius: 3px;
  }




</style>
