<script>

export default {

    name: "AppSlider"

}

</script>

<template>

    <section id="slider">

        <div class="container-xl overflow-hidden">
            
           <div class="cards flex-row-spc-btwn-center">
                <div class="card">
                    <a href=""><img src="../assets/images/client-logos-1-200x188.png" alt=""></a>
                </div>
                <div class="card">
                    <a href=""><img src="../assets/images/client-logos-2-200x188.png" alt=""></a>
                </div>
                <div class="card">
                    <a href=""><img src="../assets/images/client-logos-3-200x188.png" alt=""></a>
                </div>
           </div>
           
           

        </div>

    </section>    

</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

#slider {

    background-image: url("../assets/images/rgb-gradient-bar-for-logo-carrasel.jpg");
    // background-position: top;
    // background-repeat: no-repeat;
    background-size: cover;
    

    .cards {

        position: relative;
        animation-name: slide-left;
        animation-duration: 60s;
        animation-iteration-count: infinite;
        animation-timing-function: linear;



    }

    @keyframes slide-left {

        0% {

            opacity: 1;
            left: 100%;
            
        }

        98% {

            opacity: 1;
            left: -33%;


        }

        99% {

            opacity: 0;

        }

        100% {

            left:100%;

        }

    }


    
}


</style>