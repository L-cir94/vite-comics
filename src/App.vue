<script>
import AppHeader from "./components/AppHeader.vue"
import AppMain from "./components/AppMain.vue"
import AppFooter from "./components/AppFooter.vue"
import JumboTron from "./components/JumboTron.vue"
export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    JumboTron,
  }
}
</script>

<template>

  <AppHeader></AppHeader>
  <JumboTron></JumboTron>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>

<style lang="scss">
@use './assets/partials/variables' as*;
</style>