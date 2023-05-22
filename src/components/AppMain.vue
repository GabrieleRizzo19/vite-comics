<script>

    import MainContent from './MainContent.vue';
    import MainIconBar from './MainIconBar.vue';

    export default{
        name: "AppMain",
        components: {
            MainContent,
            MainIconBar
        }
    }

</script>

<template>

    <main>
        <div class="main-wrapper">
            <MainContent />
            <MainIconBar />
        </div>
    </main>

</template>

<style scoped>



</style>