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
                    text: 'DC Merchandise',
                    src: 'buy-comics-merchandise.png'
                },
                {
                    text: 'Subscription',
                    src: 'buy-comics-subscriptions.png'
                },
                {
                    text: 'comic shop locator',
                    src: 'buy-comics-shop-locator.png'
                },
                {
                    text: 'dc power Visa',
                    src: 'buy-dc-power-visa.svg'
                },
            ],
            comics: [
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb":"src/assets/img/Catwoman_Vol_2_1.webp",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "src/assets/img/Catwoman_Vol_2_1.webp",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "src/assets/img/Catwoman_Vol_2_1.webp",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "src/assets/img/Catwoman_Vol_2_1.webp",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "src/assets/img/Catwoman_Vol_2_1.webp",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "src/assets/img/Catwoman_Vol_2_1.webp",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "src/assets/img/Catwoman_Vol_2_1.webp",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
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
        
        <section class="comics">
            <div class="container">
                <h4 class="p-3 text-uppercase">Current series</h4>
                <div class="row">
                    <div class="col-2" v-for="comic in comics">
                        <div class="comic">
                            <img  :class="img - fluid" :src="comic.thumb" :alt="comic.series">
                            <h6 class="text-uppercase mt-2">{{ comic.series }}</h6>
                        </div>
                    </div>
                </div>
                <div class="col offset-5">
                    <button class="text-uppercase mb-3 ms-3">Load more</button>
                </div>
            </div>
        </section>

        <div class="banner">
            <div class="container">
                <div class="row">
                    <div class="col d-flex align-items-center p-2 pt-5 pb-5 " v-for="item in banner">
                        <img height="60" :src="getImageUrl(item.src)" :alt="item.text">
                        <span class="ms-3 text-uppercase">{{ item.text }}</span>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>
<style lang="scss" scoped>
@use '../assets/partials/variables' as*;


.comics {
    h4 {
        display: inline-block;
        background-color: $primary;
        margin-top: -3rem;
        margin-bottom: 3rem;
    }

    button {
        background-color: $primary;
        border: solid $primary;
        color: white;
        padding: 0 2rem;
    }
    img{
        aspect-ratio: 1;
    }
}
</style>