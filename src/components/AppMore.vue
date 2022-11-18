<script>

export default {

    name: "AppMore"
    
}

</script>

<template>

    <section id="more" class="flex-row-center-center">

        <div class="emergency col-xs-four">
            <h3 class="font-size-30">Emergency Care</h3>
            <img src="../assets/images/wave-divider.png" alt="">
            <p class="font-size-20">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae, amet adipisci debitis impedit vero saepe ut</p>
            <a class="cta secondary" href="#">LEARN MORE</a>
        </div>
        <div class="expert col-xs-four">
            <h3 class="font-size-30">Emergency Care</h3>
            <img src="../assets/images/wave-divider.png" alt="">
            <p class="font-size-20">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae, amet adipisci debitis impedit vero saepe ut</p>
            <a class="cta secondary" href="#">LEARN MORE</a>
        </div>
        <div class="superb col-xs-four">
            <h3 class="font-size-30">Emergency Care</h3>
            <img src="../assets/images/wave-divider.png" alt="">
            <p class="font-size-20">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae, amet adipisci debitis impedit vero saepe ut</p>
            <a class="cta secondary" href="#">LEARN MORE</a>
        </div>

    </section>

</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;


* {

    text-align: center;
    color: $textSecondary;

}


#more {

    padding: 0;

    .emergency,
    .expert,
    
    .superb {

        padding: 4rem 2rem;

    }

    .emergency {

        background-color: $emergencyColor;

    }

    .expert {

        background-color: $expertColor;

    }

    .superb {

        background-color: $superbColor;

    }

}
</style>