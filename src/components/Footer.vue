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
    <div class="lower">
      <div class="left">
        Enjoy the low price. We are tracking any intention of piracy.
      </div>
      <div class="right">
        © 2020 NEXGEN is Proudly Powered by <span>Codings</span>.
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
 @import '@/style/10Footer.scss';
</style>
