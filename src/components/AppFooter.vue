<script>
export default {
  name: "AppFooter",
  data() {
    return {

    }
  }
}
</script>
<template>
  <footer>
    <div class="footer_top">
      <div class="container">
        <div class="row pt-4 ">
          <div class="col-2">
            <ul>
              <h4>Dc Comics</h4>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>
            <ul>
              <h4>Shop</h4>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </div>
          <div class="col-2">
            <ul>
              <h4>Dc</h4>
              <li><a href="#">Terms Of Use</a></li>
              <li><a href="#">Privacy policy (New)</a></li>
              <li><a href="#">Ad Choices</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subscriptions</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">CPSC Certificates</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop Help</a></li>
              <li><a href="#">Contact Us</a></li>
            </ul>
          </div>
          <div class="col-2">
            <ul>
              <h4>Sites</h4>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Power Visa</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="footer_bottom">
      <div class="container d-flex justify-content-between align-items-baseline pt-4">
        <button class="p-2">SIGN-UP NOW!</button>
        <div class="d-flex align-items-baseline">
          <h4 class="m-0">Follow us</h4>
          <ul class="d-flex gap-2">
            <li>
              <a href="#">
                <img src="./../assets/img/footer-facebook.png" alt="">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="./../assets/img/footer-twitter.png" alt="">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="./../assets/img/footer-youtube.png" alt="">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="./../assets/img/footer-pinterest.png" alt="">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="./../assets/img/footer-periscope.png" alt="">
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>
<style lang="scss" scoped>
@use '../assets/partials/variables' as*;

li {
  list-style: none;
}

a {
  color: white;
  text-decoration: none;
}

.footer_bottom {
  h4 {
    color: $primary;
  }

  button {
    background-color: $darker;
    border: solid $primary;
    color: white;
  }

  height: 100px;
  background-color: $darker;
  z-index: 2;
}

.footer_top {
  height: 300px;
  background-color: $darker;
  background-image: url(../assets/img/dc-logo-bg.png), url(../assets/img/footer-bg.jpg);
  background-repeat: no-repeat, repeat-x;
  background-position: 80%, 50%;

  h4 {
    text-transform: uppercase;
  }
}
</style>