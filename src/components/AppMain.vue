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
        methods:{
            getImageUrl(name){
                return new URL(`../assets/img/${name}`, import.meta.url).href
            }
        }
}

</script>
<template>
    <main>
        <div class="banner">
            <div class="container">
                <div class="row">
                    <div class="col d-flex align-items-center" v-for="item in banner">
                        <img height="60" :src="getImageUrl(item.src)" alt="">
                        <span>{{ item.text }}</span>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>



<style lang="scss" scoped></style>