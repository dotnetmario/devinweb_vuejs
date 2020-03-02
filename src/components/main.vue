<template>
    <div class="sm:mx-12 main mx-2">
        <!-- navbar -->
        <navbar></navbar>

        <!-- jambotron -->
        <jumbotron></jumbotron>

        <!-- partners -->
        <div class="my-4 ">
            <img class="w-screen" src="../assets/imgs/partners.png" alt="">
        </div>

        <!-- testimonial -->
        <testimonial></testimonial>
    </div>
</template>

<script>
import navbar from "./navbar.vue"
import jumbotron from "./jumbotron.vue"
import testimonial from "./testimonial.vue"

export default {
    name: 'Main',
    components: {
        navbar,
        jumbotron,
        testimonial
    }
}
</script>

<style scoped>
</style>