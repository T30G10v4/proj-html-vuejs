<script>

import AppHeader from "./components/AppHeader.vue";
import AppJumbotron from "./components/AppJumbotron.vue";
import AppWelcome from "./components/AppWelcome.vue";
import AppMeet from "./components/AppMeet.vue";
import AppServices from "./components/AppServices.vue";
import AppTour from "./components/AppTour.vue";
import AppMore from "./components/AppMore.vue";
import AppAppointment from "./components/AppAppointment.vue";
import AppSlider from "./components/AppSlider.vue";
import AppFooter from "./components/AppFooter.vue";

export default {

  components: {

    
    AppHeader,
    AppJumbotron,
    AppWelcome,
    AppMeet,
    AppServices,
    AppTour,
    AppMore,
    AppAppointment,
    AppSlider,
    AppFooter
    

  },
  data() {

    return {

      links: [
                {
                    name: "HOME",
                    href: "#",
                    status: "active"
                },
                {
                    name: "ABOUT",
                    href: "#",
                    status: ""
                },
                {
                    name: "DEPARTMENTS",
                    href: "#",
                    status: ""
                },
                {
                    name: "ARTICLES",
                    href: "#",
                    status: ""
                },
                {
                    name: "MAKE APPOINTMENT",
                    href: "#",
                    status: "cta primary"
                },
            ],
            medicalDepartments: ["Cardiology","Pediatrics","Diabetes Care","Pre-natel Care","Ultrasound Echocardiogram"]


    }

  }

}

</script>

<template>

  <AppHeader />  
  <AppJumbotron />
  <AppWelcome />
  <AppMeet />
  <AppServices />
  <AppTour />
  <AppMore />
  <AppAppointment />
  <AppSlider />
  <AppFooter />

</template>

<style lang="scss">

@use "./styles/bss73.css" as *;
@use "./styles/partials/variables" as *;
@use "./styles/general.scss" as *;

html {

  font-family: 'Montserrat', sans-serif;

}

</style>
