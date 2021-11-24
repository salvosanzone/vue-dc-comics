<template>
  <div class="jumbotron">
    <div class="top-jumbo"></div>
    <div class="container">
      <h5>content goes here</h5>
    </div>
  </div>
</template>

<script>
export default {
  name:'Jumbotron'
}
</script>

<style lang="scss" scoped>
  .jumbotron{
    // display: flex;
    // justify-content: center;
    .top-jumbo{
      height: 300px;
      background-image: url(../assets/img/jumbotron.jpg);
      background-repeat: no-repeat;
      background-position: top;
      background-size: cover;
    }
    .container{
      color: white;
      //placeholder
      height: 90px;
    }
  }
 
</style>