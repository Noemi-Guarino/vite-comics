<script>
export default {
    data() {
        return {
            assets:[
            {
              img:"../assets/img/buy-comics-digital-comics.png",
            },
            {
              img:"../assets/img/buy-comics-merchandise.png",
            },
            {
              img:"../assets/img/buy-comics-subscriptions.png",
            },
            {
              img:"../assets/img/buy-comics-shop-locator.png",
            },
            {
              img:"../assets/img/buy-dc-power-visa.svg",
            },
            ]

        };
    },
    methods: {

    }
}
</script>

<template>
    <main>
        <div class="bg_main">
            <div class="container">
                <div class="top_main">
                    <span>content main</span>
                </div>
            </div>
            <div class="under_main">
                <div>
                    <div v-for="(singleimg, index) in assets">
                     <img :src="assets.img" alt="">
                    </div> 
                </div>
            </div>      
        </div>
    </main>
</template>

<style lang="scss" scoped>
</style>
