<template>
  <footer>
    <div class="container">
      <div class="left">
      <div class="title">
        <span class="title-mod">Nex</span>
        <span>Gen</span>
      </div>
      <p>A Functional HTML Template <br> for Corporate & Business.</p>
      <div class="icons">
        <i class="fas fa-phone-alt"> +1 (305) 1234-5678</i>
        <br>
        <i class="fas fa-envelope"> hello@example.com</i>
        <br>
        <i class="fas fa-map-marker-alt"> Main Avenue, 987</i>
      </div>
      <button class="btn">Get in touch</button>
    </div>

    <div class="navbar">
      <ul v-for="(el, i) in menuFooter" :key="i">
        <li class="title">
          {{ el.titolo }}
        </li>
        <li class="voci" v-for="(elem, index) in el.voci" :key="index">
          {{ elem}}
        </li>
      </ul>
    </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data() {
    return {

    menuFooter : [
      {
        titolo : 'about',
        voci : ['The Company', 'Institutional', 'Social & Events', 'Innovation', 'Environment', 'Technology']
      },
      {
        titolo : 'Services',
        voci : ['Audit & Assurance', 'Financial Advisory', 'Analytics M&A', 'Middle Marketing', 'Legal Consulting', 'Regulatory Risk']
      },
      {
        titolo : 'Support',
        voci : ['Responsability', 'Terms of Use', 'About Cookies', 'Privacy Policy', 'Accessibility', 'Information']
      },
    ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  footer {
    background-color: #121117;
  }

  .container {
    padding: 150px 0;
    margin: auto;
    width: 70%;
    display: flex;
  }

  p,.icons {
    color: lightgrey;
    font-size: 20px;
    margin: 20px;
  }

  i {
    font-size: 18px;
    margin-bottom: 15px;
  }

  .title {
    font-size: 30px;
    text-transform: uppercase;
    color: rgb(255, 255, 255);
    font-weight: 800;
    margin-left: 20px;
  }

  .title-mod {
    background-color: rgba(12, 226, 197, 0.15);
    padding: 10px 0;
    padding-left: 20px;
    padding-right: 5px;
    border-top-left-radius: 30px;
    border-bottom-left-radius: 30px;
    color: rgba(0, 250, 217, 0.692);
    margin-right: 3px;
  }

button {
    color: white;
    border: 1px solid #048383;
    background-color: transparent;
    height: 40px;
    padding: 0 18px;
    text-transform: uppercase;
    font-size: 14px;
    font-weight: bolder;
    border-radius: 3px;
    margin-right: 15px;
    margin-left: 20px;
    }

 button:hover {
    cursor: pointer;
    color: black;
    background: rgb(238,174,202);
    background: radial-gradient(circle, rgba(238,174,202,1) 0%, rgba(148,187,233,1) 100%);
}

.navbar {
  width: 900px;
  display: flex;
  margin-left: 50px;
}

ul {
  width: 250px;
  margin-right: 20px;
  background-color: rgba(255, 255, 255, 0.027);
  border-radius: 10px;
}

li {
  color: white;
  margin-bottom: 5px;
  font-weight: 400;
}

ul {
  padding-top: 30px;
}

.title {
  position: relative;
  right: 20px;
  margin-bottom: 20px;
  text-transform: capitalize;
  list-style: none;
}

.voci {
  font-size: 20px;
}
</style>
