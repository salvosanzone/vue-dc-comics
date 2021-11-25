<template>
  <div class="card">
    <img :src="comics.thumb" :alt="comics.series">
    <h6>{{comics.series}}</h6>
  </div>
</template>

<script>
export default {
  name: 'ComicsCard',
  props:{
    // comicsName : String,
    // comicsImage: String
    //sintassi alternativa
    comics: Object,
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