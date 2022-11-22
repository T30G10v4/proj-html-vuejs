<script>

export default {

    name: "AppAppointment"

}

</script>

<template>

    <section id="appointment">

        <div class="container-xl">
            
            <h2 class="underline center-white font-size-50 text-align-center text-secondary">Make An Appointment</h2>

            <p class="font-size-20 text-secondary">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt distinctio, 
                eaque, ad ratione recusandae veniam nostrum vero ut impedit inventore maiores amet facere nisi 
                atque dignissimos, deleniti totam rem at?
            </p>

            <div class="appointment-form flex-row-spc-btwn-center flex-wrap">

                <div class="col-45">
                    <input type="text" placeholder="Name*">
                </div>
                <div class="col-45">
                    <input type="text" placeholder="Email*">
                </div>
                <div class="col-45">
                    <input type="text" placeholder="Phone Number">
                </div>
                <div class="col-45">
                    <input type="date" placeholder="Appointment Date">
                </div>
                <div class="col-100">
                    <input type="text" placeholder="How can we help?*">
                </div>
            
            </div>

            <a href="#" class="cta primary">MAKE AN APPOINTMENT</a>

        </div>

    </section>    

</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

#appointment {

    background-image: url("../assets/images/make-an-appointment.jpg");
    background-position: top;
    background-repeat: no-repeat;
    background-size: cover;

    
    input {

        width:100%;
        padding: 2rem;
        font-size: 2rem;
        background: transparent;
        border: 1px solid white;
        margin-top: 3rem;

    }

    
    .cta.primary {

        display: block;
        text-align: center;
        color: $textSecondary;
        margin-top: 3rem;

    }
}


</style>