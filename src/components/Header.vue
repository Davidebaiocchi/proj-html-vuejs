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

    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
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


</style>
