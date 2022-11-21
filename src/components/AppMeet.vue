<script>

export default {

    name: "AppMeet"

}

</script>

<template>

    <section id="meet">

        <div class="container-xl">
            
            <div class="logo-img text-align-center"><img src="../assets/images/icon-5.png" alt=""></div>
                
            <h2 class="underline center-primary font-size-50 text-align-center">MEET OUR DOCTORS</h2>

            <p class="font-size-20 text-align-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam ut tempore consequatur maxime nulla cupiditate fuga explicabo, officia delectus quaerat, eaque veritatis qui vitae alias atque, quidem quo repellendus corporis!</p>

            <div class="cards flex-row-spc-btwn-center">
                <div class="card col-30">
                    <img src="../assets/images/doctor-1.jpg" alt="">
                    <div class="p-2rem">
                        <h3 class="font-size-20">JON SNOW</h3>
                        <h4 class="font-size-20">Anestestheologist</h4>
                        <p class="font-size-20">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis quibusdam facere perferendis doloremque? Omnis aliquid recusandae illum, praesentium doloremque ad dolore quidem est obcaecati, magni maiores, laudantium voluptatum voluptate nostrum!</p>
                        <a href="#"><i class="social fa-brands fa-facebook-f"></i></a><a href="#"><i class="social fa-brands fa-twitter"></i></a><a href="#"><i class="social fa-brands fa-instagram"></i></a>
                    </div>
                </div>
                <div class="card col-30">
                    <img src="../assets/images/doctor-2.jpg" alt="">
                    <div class="p-2rem">
                        <h3 class="font-size-20">TONY STARK</h3>
                        <h4 class="font-size-20">Anestestheologist</h4>
                        <p class="font-size-20">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis quibusdam facere perferendis doloremque? Omnis aliquid recusandae illum, praesentium doloremque ad dolore quidem est obcaecati, magni maiores, laudantium voluptatum voluptate nostrum!</p>
                        <a href="#"><i class="social fa-brands fa-facebook-f"></i></a><a href="#"><i class="social fa-brands fa-twitter"></i></a><a href="#"><i class="social fa-brands fa-instagram"></i></a>
                    </div>
                </div>
                <div class="card col-30">
                    <img src="../assets/images/doctor-3.jpg" alt="">
                    <div class="p-2rem">
                        <h3 class="font-size-20">ARYA STARK</h3>
                        <h4 class="font-size-20">Anestestheologist</h4>
                        <p class="font-size-20">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis quibusdam facere perferendis doloremque? Omnis aliquid recusandae illum, praesentium doloremque ad dolore quidem est obcaecati, magni maiores, laudantium voluptatum voluptate nostrum!</p>
                        <a href="#"><i class="social fa-brands fa-facebook-f"></i></a><a href="#"><i class="social fa-brands fa-twitter"></i></a><a href="#"><i class="social fa-brands fa-instagram"></i></a>
                    </div>
                </div>
            </div>

        </div>

    </section>

    

</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;


#meet {

    background-color: $backgroundColorSecondary;
    color: $textPrimary;

    .container-xl * {

        margin-bottom: 2rem;

    }

   

    .card {

        background-color: $backgroundColorPrimary;

        

    }
    

}


</style>