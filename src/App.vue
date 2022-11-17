<script>

import AppJumbotron from "./components/AppJumbotron.vue";
import AppWelcome from "./components/AppWelcome.vue";

export default {

  components: {

    AppJumbotron,
    AppWelcome

  }

}

</script>

<template>

  <AppJumbotron />
  <AppWelcome />

</template>

<style lang="scss">

@use "./styles/bss73.css" as *;
@use "./styles/partials/variables" as *;
@use "./styles/general.scss" as *;

html {

  font-family: 'Montserrat', sans-serif;

}

</style>
