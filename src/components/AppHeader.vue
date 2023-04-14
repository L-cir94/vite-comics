<script>
export default {
    name: "AppHeader",
    data() {
        return {
            menu: [
                {
                    text: 'Characters',
                    href: '#',
                    activePage: true
                },
                {
                    text: 'Comics',
                    href: '#',
                    activePage: false
                },
                {
                    text: 'Movies',
                    href: '#',
                    activePage: false
                },
                {
                    text: 'TV',
                    href: '#',
                    activePage: false
                },
                {
                    text: 'Games',
                    href: '#',
                    activePage: false
                },
                {
                    text: 'Videos',
                    href: '#',
                    activePage: false
                },
                {
                    text: 'Fans',
                    href: '#',
                    activePage: false
                },
                {
                    text: 'News',
                    href: '#',
                    activePage: false
                },
                {
                    text: 'Shop',
                    href: '#',
                    activePage: false
                },

            ]
        }
    }
}
</script>

<template>
    <header>
    <nav class="navbar navbar-expand-xxl navbar-light bg-light">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img width="50" src="../assets/img/dc-logo.png" alt="">
        </a>
        <button class="navbar-toggler d-lg-none" type="button" data-bs-toggle="collapse"
          data-bs-target="#collapsibleNavId" aria-controls="collapsibleNavId" aria-expanded="false"
          aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="Main_nav">
          <ul class="navbar-nav ms-auto mt-2 mt-lg-0">
            <li class="nav-item" v-for="item in menu ">
              <a class="nav-link" :href="item.href" aria-current="page">{{item.text}}</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
@use './assets/partials/variables' as*;

</style>