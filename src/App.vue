<template>
  <div>
    <Header />
    <Jumbotron />
    <Information />
    <Footer />

  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbotron from './components/Jumbotron.vue'
import Information from './components/Information.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Information,
    Footer
  }
}
</script>

<style lang="scss">
  @import "./assets/style/generals.scss";
  @import url('https://fonts.googleapis.com/css2?family=Lato:ital@0;1&family=Roboto&display=swap');
</style>
