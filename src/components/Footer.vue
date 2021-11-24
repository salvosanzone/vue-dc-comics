<template>
  <footer>
    <div class="top-footer">
      <div class="container">
        <div class="link-footer">
          <ul>
            <h5>DC COMICS</h5>
            <li>
              <a href="">Characters</a>
            </li>
            <li>
              <a href="">Comics</a>
            </li>
            <li>
              <a href="">Movies</a>
            </li>
            <li>
              <a href="">TV</a>
            </li>
            <li>
              <a href="">Games</a>
            </li>
            <li>
              <a href="">Videos</a>
            </li>
            <li>
              <a href="">News</a>
            </li>
            <h5>shop dc</h5>
            <li>
              <a href="">shop dc</a>
            </li>
            <li>
              <a href="">shop dc collectibles</a>
            </li>
          </ul>
          <ul>
            <h5>DC</h5>
            <li>
              <a href="">Terms of Use</a>
            </li>
            <li>
              <a href="">Privacy Policy (New)</a>
            </li>
            <li>
              <a href="">Ad Choices</a>
            </li>
            <li>
              <a href="">Adversiting</a>
            </li>
            <li>
              <a href="">Jobs</a>
            </li>
            <li>
              <a href="">Subscriptions</a>
            </li>
            <li>
              <a href="">Talent Workshops</a>
            </li>
            <li>
              <a href="">CPSC Certificates</a>
            </li>
            <li>
              <a href="">Ratings</a>
            </li>
            <li>
              <a href="">Shop Help</a>
            </li>
            <li>
              <a href="">Contact Us</a>
            </li>
          </ul>
          <ul>
            <h5>sites</h5>
            <li>
              <a href="">DC</a>
            </li>
            <li>
              <a href="">MAD Magazine</a>
            </li>
            <li>
              <a href="">DC Kids</a>
            </li>
            <li>
              <a href="">DC Universe</a>
            </li>
            <li>
              <a href="">DC Power Visa</a>
            </li>
          </ul>
        </div>
        <div class="img-footer"></div>
      </div>
    </div>
    <div class="bottom-footer">
      <div class="container">
        <div class="shop-now">
          <div class="btn-shop">
            <button>
              <a href="">sign-up now!</a>
            </button>
          </div>
        </div>
        <div class="socials">
          <h5>FOLLOW US</h5>
          <i class="fab fa-facebook"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-youtube"></i>
          <i class="fab fa-pinterest"></i>
          <i class="fas fa-map-marker-alt"></i>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="scss">
   footer{
     .top-footer{
       display: flex;
       justify-content: center;
       height: 265px;
       background-image: url(../assets/img/footer-bg.jpg);
       .container{
         color: white;
         .img-footer{
           width: 400px;
           height: 100%;
           background-image: url("../assets/img/dc-logo-bg.png");
           background-position: center;
           background-repeat: no-repeat;
           background-size: cover;
         }
           .link-footer{
             display: flex;
             a{
               font-size: 8px;
               text-transform: none;
             }
           }
       }
       h5{
         text-transform: uppercase;
         padding-left: 5px;
         margin: 10px 0;
       }
       a{
         color: #959595;
       }
     }

     .bottom-footer{
       display: flex;
       justify-content: center;
       height: 80px;
       background-color: #303030;
       .container{
         padding: 5px;
         button{
           background-color: #303030;
           padding: 8px 10px;
           border-collapse: collapse;
           border: 2px solid #0282F9;
           a{
             color: white;
             margin: 0;
           }
         }
         h5{
           margin-right: 10px;
           color: #1B65E7;
         }
         .socials{
           display: flex;
           align-items: center;
         }
       }
     }



   }

</style>