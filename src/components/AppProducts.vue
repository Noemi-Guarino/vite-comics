<script>


export default {
    data() {
        return {
        };
    },
    props: {
        products: Object,
        img:String,
        title:String,
        price:String,
    },
    methods: {

    }
}
</script>

<template>
    <div class="card">
        <div class="card_img">
            <img :src="img" :alt="title">
        </div>
        <div class="card_info">
            <h3>
                {{ title }}
            </h3>
            <h6>
                {{ price }}
            </h6>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.card {
    // border: 1px solid red;
    margin: 10px;
    width: calc(100% / 6 - 20px);
    margin-bottom: 10px;
 }

    .card_img{
    //  border: 2px solid blue;
     height: 200px;
     overflow: hidden;
    }

    h3{
        color: white;
        font-size: 1.5rem;
    }

    h6{
        color: red;
        font-size: 1.2rem;
    }
</style>