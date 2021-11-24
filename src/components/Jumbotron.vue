<template>
  <div class="jumbotron">
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
    display: flex;
    justify-content: center;
    .container{
      color: white;
      //placeholder
      height: 90px;
    }
  }
 
</style>