<script>

export default {

    name: "AppTour"
    
}

</script>

<template>

    <section id="tour">

        <div class="container-xl ">

            <img src="../assets/images/icon-7.png" alt="">
            <h2 class="underline center-white font-size-50 ">TOUR OUR FACILITIES</h2>
             <p class="font-size-20 ">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam ut tempore consequatur maxime nulla cupiditate fuga explicabo, officia delectus quaerat, eaque veritatis qui vitae alias atque, quidem quo repellendus corporis!</p>
             <a href="#"><img class="play-button" src="../assets/images/play-icon.png" alt=""></a>

        </div>

    </section>

</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;


* {

    text-align: center;
    color: $textSecondary;

}


#tour {

    background-image: url("../assets/images/paralax-bg-tour-facilities.jpg");
    background-position: top;
    background-repeat: no-repeat;
    background-size: cover;

    .play-button {

        margin-top: 3rem;

    }

}
</style>