<script>

export default {

    name: "AppMeet"

}

</script>

<template>

    <section id="meet">

        <div class="container-xl">
            
            <div class="logo-img text-align-center"><img src="../assets/images/icon-5.png" alt=""></div>
                
            <h2 class="font-size-50 text-align-center">MEET OUR DOCTORS</h2>

            <p class="font-size-20 text-align-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam ut tempore consequatur maxime nulla cupiditate fuga explicabo, officia delectus quaerat, eaque veritatis qui vitae alias atque, quidem quo repellendus corporis!</p>

            <div class="cards flex-row-spc-btwn-center">
                <div class="card col-30">
                    <img src="../assets/images/doctor-1.jpg" alt="">
                    <div class="p-2rem">
                        <h3 class="font-size-20">JON SNOW</h3>
                        <h4 class="font-size-20">Anestestheologist</h4>
                        <p class="font-size-20">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis quibusdam facere perferendis doloremque? Omnis aliquid recusandae illum, praesentium doloremque ad dolore quidem est obcaecati, magni maiores, laudantium voluptatum voluptate nostrum!</p>
                        <i class="fa-brands fa-facebook-f"></i><i class="fa-brands fa-twitter"></i><i class="fa-brands fa-instagram"></i>
                    </div>
                </div>
                <div class="card col-30">
                    <img src="../assets/images/doctor-2.jpg" alt="">
                    <div class="p-2rem">
                        <h3 class="font-size-20">TONY STARK</h3>
                        <h4 class="font-size-20">Anestestheologist</h4>
                        <p class="font-size-20">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis quibusdam facere perferendis doloremque? Omnis aliquid recusandae illum, praesentium doloremque ad dolore quidem est obcaecati, magni maiores, laudantium voluptatum voluptate nostrum!</p>
                        <i class="fa-brands fa-facebook-f"></i><i class="fa-brands fa-twitter"></i><i class="fa-brands fa-instagram"></i>
                    </div>
                </div>
                <div class="card col-30">
                    <img src="../assets/images/doctor-3.jpg" alt="">
                    <div class="p-2rem">
                        <h3 class="font-size-20">ARYA STARK</h3>
                        <h4 class="font-size-20">Anestestheologist</h4>
                        <p class="font-size-20">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis quibusdam facere perferendis doloremque? Omnis aliquid recusandae illum, praesentium doloremque ad dolore quidem est obcaecati, magni maiores, laudantium voluptatum voluptate nostrum!</p>
                        <i class="fa-brands fa-facebook-f"></i><i class="fa-brands fa-twitter"></i><i class="fa-brands fa-instagram"></i>
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

    h2::after {

        content: "";
        display: block;
        margin: 2rem auto;
        width: 33%;
        background-color: $textPrimary;
        height: 2px;

    }

    .card {

        background-color: $backgroundColorPrimary;

        i {

            font-size: 2rem;
            text-align: center;
            line-height: 30px;
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 4px;
            margin-right: 1rem;

        }

        
        .fa-facebook-f {

            background-color: $fbColor;

        }

        .fa-twitter {

            background-color: $twColor;

        }

        .fa-instagram {

            background-color: $igColor;

        }

    }
    

}


</style>