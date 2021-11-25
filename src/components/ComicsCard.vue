<template>
  <div class="card">
    <img :src="comicsImage" alt="comicsName">
    <h6>{{comicsName}}</h6>
  </div>
</template>

<script>
export default {
  name: 'ComicsCard',
  props:{
    comicsName : String,
    comicsImage: String
  }
}
</script>

<style lang="scss">
  .card{
    //width: calc(100% / 6 - 20px);
    width: 110px;
    height: 110px;
    margin: 10px;
    text-align: center;
    img{
      width: 100%;
      object-fit: cover;
      object-position: top;

    }
  }
</style>