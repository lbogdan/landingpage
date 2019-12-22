<template>
    <a class="buy-btn" v-bind:href="url">{{text}}</a>
</template>

<script>
    export default {
        name: "BuyButton",
        props:{
            url: String,
            text: String,
        }
    }
</script>

<style scoped>

</style>