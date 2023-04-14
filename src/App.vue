<script>
import AppHeader from "./components/AppHeader.vue"
import AppMain from "./components/AppMain.vue"
import AppFooter from "./components/AppFooter.vue"
import AppBanner from "./components/AppBanner.vue"
export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    AppBanner
  }
}
</script>

<template>
  <!--   <AppMain></AppMain>
    <AppHeader></AppHeader>
    <AppFooter></AppFooter> -->

  <header>
    <nav class="navbar navbar-expand-xxl navbar-light bg-light">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img width="50" src="./assets/img/dc-logo.png" alt="">
        </a>
        <button class="navbar-toggler d-lg-none" type="button" data-bs-toggle="collapse"
          data-bs-target="#collapsibleNavId" aria-controls="collapsibleNavId" aria-expanded="false"
          aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="Main_nav">
          <ul class="navbar-nav ms-auto mt-2 mt-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="#" aria-current="page">Characters</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#" aria-current="page">Comics</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
  <main>
<div class="container">
  <div class="row">
    <div class="col">
      <img height="60px" src="./assets/img/buy-comics-digital-comics.png" alt="">
      <span>Digital Comics</span>
    </div>
    <div class="col">
      <img height="60px" src="./assets/img/buy-comics-digital-comics.png" alt="">
      <span>Digital Comics</span>
    </div>
    <div class="col">
      <img height="60px" src="./assets/img/buy-comics-digital-comics.png" alt="">
      <span>Digital Comics</span>
    </div>
    <div class="col">
      <img height="60px" src="./assets/img/buy-comics-digital-comics.png" alt="">
      <span>Digital Comics</span>
    </div>
    <div class="col">
      <img height="60px" src="./assets/img/buy-comics-digital-comics.png" alt="">
      <span>Digital Comics</span>
    </div>
  </div>
</div>
  </main>
  <footer>
    <div class="footer_top">

    </div>
    <div class="footer_bottom">

    </div>
  </footer>
</template>

<style lang="scss">
</style>