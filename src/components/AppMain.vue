<script>
export default {

    name: "AppMain",

    data() {
        return {
            banner: [
                {
                    text: 'Digital Comics',
                    src: 'buy-comics-digital-comics.png'
                },
                {
                    text: 'Digital Comics',
                    src: 'buy-comics-merchandise.png'
                },
                {
                    text: 'Digital Comics',
                    src: 'buy-comics-subscriptions.png'
                },
                {
                    text: 'Digital Comics',
                    src: 'buy-comics-shop-locator.png'
                },
                {
                    text: 'Digital Comics',
                    src: 'buy-dc-power-visa.svg'
                },
            ]
        }
    },
    methods: {
        getImageUrl(name) {
            return new URL(`../assets/img/${name}`, import.meta.url).href
        }
    }
}

</script>
<template>
    <main>
        <div class="container-fluid">
            <div class="jumbotron">

            </div>
        </div>
        
        <div class="banner">
            <div class="container">
                <div class="row">
                    <div class="col d-flex align-items-center p-5 " v-for="item in banner">
                        <img height="60" :src="getImageUrl(item.src)" alt="">
                        <span class="ms-3">{{ item.text }}</span>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>
<style lang="scss" scoped>
@use '../assets/partials/variables' as*;

.jumbotron {
height: 400px;
    background-image: url(../assets/img/jumbotron.jpg);
    background-size: cover;
}
</style>