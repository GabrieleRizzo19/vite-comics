<script>

    import MainContentCards from './MainContentCards.vue';

    export default{
        name: "MainContent",
        components: {
            MainContentCards
        }
    }

</script>

<template>

    <div class="main-content-wrapper">
        <div class="container">

            <MainContentCards />

        </div>
    </div>

</template>

<style lang="scss" scoped>

    .main-content-wrapper{
        background-color: black;
        color: white;
        text-align: center;
    }

</style>