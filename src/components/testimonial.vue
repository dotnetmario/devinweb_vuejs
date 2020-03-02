<template>
    <div class="my-16 flex">
        <div class="w-full block flex-growss md:flex md:items-center md:w-auto">
            <div class="w-full mx-auto md:w-1/2 img-testimonial sm:mx-5">

                <div class="bg-testimonial p-1 p-8 md:ml-5 md:ml-2 md:mt-56">
                    <p class="block w-full pl-5 text-white mb-8 border-l-2 border-white-300">Lorem ipsum dolor sit, amet consectetur adipisicing 
                        elit. Ullam eveniet officia fugiat laboriosam labore.</p>

                    <div class="w-full flex">
                        <div class="flex-1">
                            <img class="rounded-full h-16 w-16 inline" src="../assets/imgs/profile.jpg" alt="">
                            <p class="text-white inline ml-2 lg:ml-5">SAM B.</p>
                        </div>

                        <div class="flex-1 align-middle">
                            <div class="text-right block">
                                <fntawsm :icon="['fas', 'star']" class="text-yellow-500"/>
                                <fntawsm :icon="['fas', 'star']" class="text-yellow-500"/>
                                <fntawsm :icon="['fas', 'star']" class="text-yellow-500"/>
                                <fntawsm :icon="['fas', 'star']" class="text-yellow-500"/>
                                <fntawsm :icon="['fas', 'star']" class="text-yellow-500"/>
                            </div>
                            <p class="text-white text-right block ">28 reviews at Yelp</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="w-full mx-auto md:w-1/2 sm:mx-5">
                <p class="text-xs font-bold mb-5">01 <span class="h-1 w-12 align-middle mx-3 inline-block bg-testimonial"></span> ABOUT US</p>
                <h1 class="mb-5 text-4xl">Let's make cities better</h1>

                <p class="mb-5 text-gray-600">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Magnam aperiam veniam itaque necessitatibus sit nisi numquam repellat nostrum, qui eaque animi at accusamus, ad dolores corporis deserunt, iure odit aliquam incidunt consequatur atque. Officiis aliquid iste necessitatibus. Hic, laudantium ad dolorum, voluptatem animi id mollitia facilis ea, similique accusamus ipsam.</p>

                <p class="mb-5 text-gray-600">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Mollitia quis eaque consectetur quo deserunt eos recusandae excepturi maxime dicta ullam!</p>

                <br class="mb-5">

                <div class="mb-5 flex">
                    <img class="flex-1 rounded-full h-16 w-16 inline align-left" src="../assets/imgs/profile.jpg" alt="">
                    <div class="inline w-full float-right ml-5">
                        <p class="text-gray-600">Lorem, ipsum dolor?</p>
                        <p class="text-gray-800 font-bold">Lorem, ipsum dolor dolor dolor. <fntawsm :icon="['fa', 'arrow-right']" class="ml-2"/></p>
                    </div>
                    <!-- <div class="inline w-full float-right">
                        <p class="text-gray-600 inline align-left-top ml-3">Lorem, ipsum dolor.</p>
                        <p class="inline align-bottom ">Lorem, ipsum dolor dolor dolor. </p>
                    </div> -->
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "testimonial",
}
</script>

<style scoped>
    .bg-testimonial {
        background-color: rgb(51, 52, 86);
        /* margin-bottom:  */
    }

    .img-testimonial {
        background-image: url("../assets/imgs/testimonial.jpg");
         background-repeat: no-repeat;
         height: 432px;
    }
</style>