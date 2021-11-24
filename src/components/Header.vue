<template>
  <header>
    <div class="container">
      <div class="logo">
      <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <div class="menu">
      <ul>
        <li>
          <a href="#">CHARACTERS</a>
          <a class="active" href="#">COMICS</a>
          <a href="#">MOVIES</a>
          <a href="#">TV</a>
          <a href="#">GAMES</a>
          <a href="#">COLLECTIBILES</a>
          <a href="#">VIDEOS</a>
          <a href="#">FANS</a>
          <a href="#">NEWS</a>
          <a href="#">SHOP</a>
        </li>
      </ul>
    </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="scss">
  header{
    display: flex;
    justify-content: center;
    height: 90px;
    border: 1px solid black;
    .container{
      border: 1px solid black;
    }
    .logo{
      width: 60px;
      height: 60px;
    }
    ul li a{
      font-weight: bold;
      &.active{
        color: #0282F9;
      }
    }
    
  }
</style>