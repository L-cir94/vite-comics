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
        <div class="row pt-3">
          <div class="col-2">
            <h4>Dc Comics</h4>
            <ul>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>
            <h4>Shop</h4>
            <ul>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </div>
          <div class="col-2">
            <h4>Dc</h4>
            <ul>
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
            <h4>Dc Comics</h4>
            <ul>
              <li>
                <a href="#">lista footer</a>
              </li>
              <li>
                <a href="#">lista footer</a>
              </li>
              <li>
                <a href="#">lista footer</a>
              </li>
              <li>
                <a href="#">lista footer</a>
              </li>
              <li>
                <a href="#">lista footer</a>
              </li>
              <li>
                <a href="#">lista footer</a>
              </li>
              <li>
                <a href="#">lista footer</a>
              </li>
              <li>
                <a href="#">lista footer</a>
              </li>
              <li>
                <a href="#">lista footer</a>
              </li>
              <li>
                <a href="#">lista footer</a>
              </li>
              <li>
                <a href="#">lista footer</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="footer_bottom">
        <div class="container d-flex justify-content-between align-items-center p-3">
          <button class="p-2">SIGN-UP NOW!</button>
          <div class="d-flex align-items-center">
            <h4 class="m-0 me-5">Follow us</h4>
            <ul class="d-flex align-items-center gap-2">
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

</style>