<template>
  <header>
    <div class="container">
      <div class="logo">
      <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <div class="menu">
      <ul>
        <li v-for="(link, index) in menu" :key="index">
          <a :class="{active: link.current === true}" :href="link.url">{{link.text}}</a>
        </li>
      </ul>
    </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  // sintassi alternativa -> props:['menu'],
  props:{
    menu: Array
  },
  data(){
    return{
      //qui inserisco i data
      
    }

  }
}
</script>

<style lang="scss">
  header{
    display: flex;
    justify-content: center;
    height: 90px;
    background-color: white;
    .container{
      ul{
        display: flex;
      }
    }
    .logo{
      width: 60px;
      height: 60px;
    }
    ul li a{
      font-weight: bold;
      &:hover,
      &.active{
        color: #0282F9;
        border-bottom: 2px solid #0282F9;
        
      }
    }
    
  }
</style>