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
            <h2>
                {{ title }}
            </h2>
            <h6>
                {{ price }}
            </h6>
        </div>
    </div>
</template>

<style lang="scss" scoped>
</style>