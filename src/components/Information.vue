<template>
  <div class="information">
    <div class="container">
      <ul>
        <li>
          <div class="img-info">
            <img src="../assets/img/buy-comics-digital-comics.png" alt=""> 
          </div>
          <a href="">DIGITAL COMICS</a>
        </li>
        <li>
          <div class="img-info">
            <img src="../assets/img/buy-comics-merchandise.png" alt=""> 
          </div>
          <a href="">dc merchandise</a>
        </li>
        <li>
          <div class="img-info">
            <img src="../assets/img/buy-comics-subscriptions.png" alt=""> 
          </div>
          <a href="">subscription</a>
        </li>
        <li>
          <div class="img-info">
            <img src="../assets/img/buy-comics-shop-locator.png" alt=""> 
          </div>
          <a href="">comic shop locator</a>
        </li>
        <li>
          <div class="img-info">
            <img src="../assets/img/buy-dc-power-visa.svg" alt=""> 
          </div>
          <a href="">dc power visa</a>
        </li>
        
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Information'
}
</script>

<style lang="scss">
  .information{
    display: flex;
    justify-content: center;
    height: 100px;
    background-color: #0282F9;
    .container{
      ul{
        display: flex;
      }
      li{
        display: flex;
        align-items: center;
        margin: 0 10px;
        a{
          color: white;
        }
      }
      .img-info{
        width: 40px;
        height: 40px;
      }      
    }
  }
</style>