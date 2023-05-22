<script>

    import MainContent from './MainContent.vue';
    import MainIconBar from './MainIconBar.vue';
    import MainJumbotron from './Jumbotron.vue';


    export default{
        name: "AppMain",
        components: {
            MainContent,
            MainIconBar,
            MainJumbotron
        }
    }

</script>

<template>

    <main>
        <div class="main-wrapper">
            <MainJumbotron />
            <MainContent />
            <MainIconBar />
        </div>
    </main>

</template>

<style scoped>



</style>