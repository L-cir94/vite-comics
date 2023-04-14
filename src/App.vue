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

  <AppHeader></AppHeader>
  <main>
<div class="container">
  <div class="row">
    <div class="col">
      <img height="60px" src="./assets/img/buy-comics-digital-comics.png" alt="">
      <span class="ms-2">Digital Comics</span>
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
@use './assets/partials/variables' as*;

</style>