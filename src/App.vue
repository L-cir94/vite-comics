<script>
import AppHeader from "./components/AppHeader.vue"
import AppMain from "./components/AppMain.vue"
import AppFooter from "./components/AppFooter.vue"
export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  <header>
    <div class="container">
      <div class="row">
        <div class="logo">
          <img width="20" src="../src/assets/img/dc-logo.png" alt="">
        </div>
        <div class="nav">
          <ul class="d-flex">
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
          </ul>
        </div>
      </div>
    </div>
  </header>
  <main>
    <section class="content">
      <div class="container">
        <h1>Your content here</h1>
      </div>
    </section>
    <section class="jumbutron">
      <div class="container">
        <div class="row">
          <div class="col p-5">
            <img width="30" class="img-fluid" src="../src/assets/img/buy-comics-digital-comics.png" alt="">
          </div>
          <div class="col p-5">
            <img width="30" class="img-fluid" src="../src/assets/img/buy-comics-merchandise.png" alt="">
          </div>
          <div class="col p-5">
            <img width="30" class="img-fluid" src="../src/assets/img/buy-comics-subscriptions.png" alt="">
          </div>
          <div class="col p-5">
            <img width="30" class="img-fluid" src="../src/assets/img/buy-comics-shop-locator.png" alt="">
          </div>
          <div class="col p-5">
            <img width="30" class="img-fluid" src="../src/assets/img/buy-dc-power-visa.svg" alt="">
          </div>
        </div>
      </div>
    </section>
  </main>
  <footer>
    <div class="footer_top">

    </div>
    <div class="footer_bottom">

    </div>
  </footer>
</template>

<style lang="scss"></style>