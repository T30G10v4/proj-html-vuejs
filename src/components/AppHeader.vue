<script>

export default {

    name: "AppHeader",
    data() {

        return {

            links: [
                {
                    name: "HOME",
                    href: "#",
                    status: "active"
                },
                {
                    name: "ABOUT",
                    href: "#",
                    status: ""
                },
                {
                    name: "DEPARTMENTS",
                    href: "#",
                    status: ""
                },
                {
                    name: "ARTICLES",
                    href: "#",
                    status: ""
                },
                {
                    name: "MAKE APPOINTMENT",
                    href: "#",
                    status: "cta primary"
                },
            ]

        }

    }

}

</script>

<template>

    <header class="flex-row-spc-btwn-center">

      <a href="#"><img src="../assets/images/medical_logo_1x_light.png" alt=""></a>

      <ul class="flex-row-end-center">

        <li v-for="link in links">
        
            <a :class="`${link.status}`" :href="`${link.href}`">{{ link.name }}</a>

        </li>

      </ul>

    </header>

</template>

<style lang="scss" scoped>

@use "../styles/partials/variables" as *;

header {

    position: absolute;

    top: 0;
    left: 0;

    width: 100%;

    padding: 2rem 4rem;
    font-size: 2rem;

    color: $textSecondary;

    ul {

        list-style-type: none;

        li {

            margin-left: 3rem;

            a {

                text-decoration: none;
                color: inherit;

                &.active {

                    color: $colorPrimary;

                }


            }

        }

    }

}

</style>