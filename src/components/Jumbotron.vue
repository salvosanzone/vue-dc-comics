<template>
  <div class="jumbotron">
    <div class="top-jumbo"></div>
    <div class="bottom-jumbo">
      <div class="container">
        <ComicsCard 
        v-for="(comics, index) in comicsList" 
        :key="index" 
        :comics="comics"/>
      </div>
      <button>Load more</button>
    </div>
      
    
  </div>
</template>

<script>
import ComicsCard from './ComicsCard.vue';
import comicsList from '../assets/data/comicsData.js'
export default {
  name:'Jumbotron',
  components: {
    ComicsCard
  },
  data(){
    return{
      comicsList,
    }
  }
}
</script>

<style lang="scss" scoped>
  .jumbotron{
    
    .top-jumbo{
      height: 300px;
      background-image: url(../assets/img/jumbotron.jpg);
      background-repeat: no-repeat;
      background-position: top;
      background-size: cover;
    }

    .bottom-jumbo{
      display: flex;
      justify-content: center;
      flex-direction: column;
      align-items: center;
      padding: 20px 0 15px 0;
      background-color: #1C1C1C;
      button{
        background-color: #0282F9;
        color: white;
        border: none;
        padding: 7px 35px;
        cursor: pointer;
      }
    }
    .container{
      flex-wrap: wrap;
      align-items: flex-start;
      align-content: flex-start;
      margin-bottom: 50px;
      color: white;
      
    }
  }
 
</style>