<script>

export default {

    name: "AppSlider"

}

</script>

<template>

    <section id="slider">

        <div class="container-xl">
            
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

    
}


</style>