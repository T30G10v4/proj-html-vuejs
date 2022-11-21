<script>

export default {

    name: "AppFooter",
    props: {

        medicalDepartments: Array

    }

}

</script>

<template>

    <section id="footer">

        <div class="high-footer">
            <div class="columns flex-row-center-start">
                <div class="col-xs-four p-4rem">
                    <img src="../assets/images/medical_logo_1x_dark.png" alt="">
                    <p class="underline all-primary font-size-15">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quibusdam deleniti, quasi animi adipisci nihil odio maiores fugiat magni laboriosam totam nesciunt? Repellendus esse odit magnam corrupti saepe ipsa minus sapiente.</p>
                    <p class="font-size-20">LEARN MORE ABOUT US</p>
                    <a href="#"><i class="social fa-brands fa-facebook-f"></i></a>
                    <a href="#"><i class="social fa-brands fa-twitter"></i></a>
                    <a href="#"><i class="social fa-brands fa-youtube"></i></a>
                    <a href="#"><i class="social fa-brands fa-instagram"></i></a>
                </div>
                <div class="col-xs-four p-4rem">
                    <h2 class="underline start-blue">CONTACT INFORMATION</h2>
                    <div class="address font-size-15"><i class="fa-solid fa-location-dot primary-color"></i><span class="m-left-1rem">121 King Street, London, United Kingdom</span></div>
                    <div class="telephone font-size-15"><i class="fa-solid fa-phone-flip primary-color"></i><span class="m-left-1rem">1.800.458.556</span></div>

                </div>
                <div class="col-xs-four p-4rem">
                    <h2 class="underline start-blue">MEDICAL DEPARTMENTS</h2>
                    <ul>
                        
                        <li class="department" v-for="(department) in medicalDepartments"><a href="#">{{ department }}</a></li>

                    </ul>
                    <a class="cta third" href="#">VIEW OUR DEPARTMENTS</a>
                </div>
            </div>
        </div>
        <div class="low-footer p-4rem font-size-15">
            &COPY; Copyright 2022 | AbraCadabres Theme By Boolean | All Lefts Reserved | Powered by &hearts; and Boolean
        </div>
       

    </section>    

</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

#footer {

    padding: 0;

    h2 {

        font-size: 2rem;

    }

    ul {

        list-style-type: none;
        text-decoration: none;
        color: inherit;
        vertical-align: center;

        li {

            margin: 1rem 0;

        }

    }

    .low-footer {

        background-color: $backgroundColorSecondary;

    }

    
}


</style>