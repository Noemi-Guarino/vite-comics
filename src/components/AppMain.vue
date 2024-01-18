<script>
export default {
    data() {
        return {
            assets:[
            {
              img:"./src/assets/img/buy-comics-digital-comics.png",
            },
            {
              img:"./src/assets/img/buy-comics-merchandise.png",
            },
            {
              img:"./src/assets/img/buy-comics-subscriptions.png",
            },
            {
              img:"./src/assets/img/buy-comics-shop-locator.png",
            },
            {
              img:"./src/assets/img/buy-dc-power-visa.svg",
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
        </div>
        <div class="under_main">
            <div class="under_main_content" >
                <div class="assets_container_img" v-for="(singleimg,index) in assets">
                    <img :src="singleimg.img" alt="">
                </div> 
            </div>
        </div>      
        
    </main>
</template>

<style lang="scss" scoped>
</style>
