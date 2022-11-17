<script>

export default {

    name: "AppWelcome"

}

</script>

<template>

    <section id="welcome" class="text-align-center">

        <div class="container-xl">
            
            <h2 class="font-size-50">Welcome to Avada Health</h2>

            <p class="font-size-20">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt distinctio, 
                eaque, ad ratione recusandae veniam nostrum vero ut impedit inventore maiores amet facere nisi 
                atque dignissimos, deleniti totam rem at?
            </p>

            <div class="cards flex-row-spc-btwn-center">
                <div class="card col-20">
                    <img src="../assets/images/icon-1.png" alt="">
                    <h3 class="font-size-20">SAME DAY APPOINTMENTS</h3>
                    <p class="font-size-15">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat, a ducimus!</p>
                </div>
                <div class="card col-20">
                    <img src="../assets/images/icon-2.png" alt="">
                    <h3 class="font-size-20">WORLD CLASS FACILITIES</h3>
                    <p class="font-size-15">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat, a ducimus!</p>
                </div>
                <div class="card col-20">
                    <img src="../assets/images/icon-3.png" alt="">
                    <h3 class="font-size-20">EXPERT DOCTORS</h3>
                    <p class="font-size-15">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat, a ducimus!</p>
                </div>
                <div class="card col-20">
                    <img src="../assets/images/icon-4.png" alt="">
                    <h3 class="font-size-20">COMPLEMENTARY THERAPIES</h3>
                    <p class="font-size-15">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat, a ducimus!</p>
                </div>
            </div>

        </div>

    </section>

    

</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

#welcome {

    
    color: $textPrimary;

    .cards * {

        margin-top: 1rem;

    }

}


</style>