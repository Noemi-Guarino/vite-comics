<script>
// importazione componente appproducts
import AppProducts from './AppProducts.vue';


export default {
    data() {
        return {
            assets:[
            {
              img:"./src/assets/img/buy-comics-digital-comics.png",
              title:'DIGITAL COMICS',
            },
            {
              img:"./src/assets/img/buy-comics-merchandise.png",
              title:'DC MERCHANDISE',
            },
            {
              img:"./src/assets/img/buy-comics-subscriptions.png",
              title:'SUBSCRIPTION',
            },
            {
              img:"./src/assets/img/buy-comics-shop-locator.png",
              title:'COMIC SHOP LOCATOR',
            },
            {
              img:"./src/assets/img/buy-dc-power-visa.svg",
              title:'DS POWER VISA',
            },
            ]
        };
    },
      // dichiarazione del componente all'interno dell'oggetto
    components:{
    AppProducts
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
                    <!-- utilizzo del componente -->
                <AppProducts/>
                </div>
            </div>
        </div>
        <div class="under_main">
            <div class="under_main_content" >
                <div class="assetsitems" v-for="(elem,index) in assets">
                    <div class="assets_container_img">
                        <img :src="elem.img" alt="">
                    </div> 
                    <div>{{ elem.title}}</div>
                </div>
            </div>
        </div>      
        
    </main>
</template>

<style lang="scss" scoped>
</style>
