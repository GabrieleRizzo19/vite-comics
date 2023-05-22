<script>

    import FooterTop from './FooterTop.vue';

    export default{
        name: "AppFooter",
        components:{
            FooterTop
        }
    }

</script>

<template>

    <footer>
        <FooterTop />
    </footer>

</template>

<style scoped>

    footer{
        height: 500px;
        border: 2px solid black;
    }

</style>