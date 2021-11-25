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
          isActive: false
        },
        {
          url:'/',
          text:'COMICS',
          isActive: true
        },
        {
          url:'/',
          text:'MOVIES',
          isActive: false
        },
        {
          url:'/',
          text:'TV',
          isActive: false
        },
        {
          url:'/',
          text:'GAMES',
          isActive: false
        },
        {
          url:'/',
          text:'COLLECTIBILES',
          isActive: false
        },
        {
          url:'/',
          text:'VIDEOS',
          isActive: false
        },
        {
          url:'/',
          text:'FANS',
          isActive: false
        },
        {
          url:'/',
          text:'NEWS',
          isActive: false
        },
        {
          url:'/',
          text:'SHOP',
          isActive: false
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
