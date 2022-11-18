<script>

import AppJumbotron from "./components/AppJumbotron.vue";
import AppWelcome from "./components/AppWelcome.vue";
import AppMeet from "./components/AppMeet.vue";
import AppServices from "./components/AppServices.vue";
import AppTour from "./components/AppTour.vue";
import AppMore from "./components/AppMore.vue";
import AppAppointment from "./components/AppAppointment.vue";

export default {

  components: {

    AppJumbotron,
    AppWelcome,
    AppMeet,
    AppServices,
    AppTour,
    AppMore,
    AppAppointment

  }

}

</script>

<template>

  <AppJumbotron />
  <AppWelcome />
  <AppMeet />
  <AppServices />
  <AppTour />
  <AppMore />
  <AppAppointment />

</template>

<style lang="scss">

@use "./styles/bss73.css" as *;
@use "./styles/partials/variables" as *;
@use "./styles/general.scss" as *;

html {

  font-family: 'Montserrat', sans-serif;

}

</style>
