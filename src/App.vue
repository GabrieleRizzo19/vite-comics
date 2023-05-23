<script>

  import AppHeader from './components/AppHeader.vue';
  import AppMain from './components/AppMain.vue';
  import AppFooter from './components/AppFooter.vue';

  export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  data() {
    return {
      headerLink: [
        "CHARACTERS",
        "COMICS",
        "MOVIES",
        "TV",
        "GAMES",
        "COLLECTIBLES",
        "VIDEOS",
        "FANS",
        "NEWS",
        "SHOP"
      ]
    }
  }
}

</script>

<template>

  <AppHeader :headerLink="headerLink"/>

  <AppMain />

  <AppFooter />

</template>

<style lang="scss">

  @use './styles/general.scss' as *;

</style>
