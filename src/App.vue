<template>
  <div>
    <Header :menu="links" />
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
  data(){
    return{
      links:[
        {
          url:'/',
          text:'CHARACTERS',
          current: false
        },
        {
          url:'/',
          text:'COMICS',
          current: true
        },
        {
          url:'/',
          text:'MOVIES',
          current: false
        },
        {
          url:'/',
          text:'TV',
          current: false
        },
        {
          url:'/',
          text:'GAMES',
          current: false
        },
        {
          url:'/',
          text:'COLLECTIBILES',
          current: false
        },
        {
          url:'/',
          text:'VIDEOS',
          current: false
        },
        {
          url:'/',
          text:'FANS',
          current: false
        },
        {
          url:'/',
          text:'NEWS',
          current: false
        },
        {
          url:'/',
          text:'SHOP',
          current: false
        },
      ]
    }
  },
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
