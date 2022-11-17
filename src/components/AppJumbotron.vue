<script>

import AppHeader from './AppHeader.vue';

export default {

    name: "AppJumbotron",

    components: {

      AppHeader

}

}

</script>

<template>

  <section id="jumbotron">

    <AppHeader />

    <div class="container-xl">

      <div class="title position-center-y col-55">

        <h1 class="font-size-50 m-btm-2rem">Caring <span class="primary-color">For Life</span></h1>

        <h2>Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus earum id ea, distinctio quae quia asperiores molestias illum dolorem, commodi laudantium voluptates neque deleniti totam eligendi saepe esse placeat facilis!</h2>
        <a class="cta primary m-top-2rem" href="#">LEARN MORE</a>
    
      </div>

    </div>

  </section>

</template>

<style lang="scss" scoped>

#jumbotron {

  

  background-image: url("../assets/images/header-image-homepage.jpg");
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;

  
  
  height: 75vh;

  color: white;

  .container-xl {

    height: 100%;
    position: relative;

  }

}

</style>