<template>
    <swiper 
    :modules="modules" 
    :slides-per-view="1" 
    :pagination="{clickable: true}"
    class="pb-8">

        <swiper-slide class="grid place-items-center">
        <img src="../assets/images/home1-img.webp" alt="" class="w-2/3 lg:w-[90%]">
        </swiper-slide>

        <swiper-slide class="grid place-items-center">
        <img src="../assets/images/slider_img1.webp" alt="" class="w-2/3 lg:w-[90%]">
        </swiper-slide>

        <swiper-slide class="grid place-items-center">
        <img src="../assets/images/slider_img2.webp" alt="" class="w-2/3 lg:w-[90%]">
        </swiper-slide>

        <swiper-slide class="grid place-items-center">
        <img src="../assets/images/slider_img3.webp" alt="" class="w-2/3 lg:w-[90%]">
        </swiper-slide>

        <swiper-slide class="grid place-items-center">
        <img src="../assets/images/slider_img4.webp" alt="" class="w-2/3 lg:w-[90%]">
        </swiper-slide>
        
       
    </swiper>
</template>

<script setup>
import  { Pagination } from "swiper";
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";
// import Swiper and modules styles
import "swiper/css";
import "swiper/css/navigation";


const modules = [Pagination];
</script>



<style scoped>

.swiper-pagination-bullet{

    @apply w-3 h-3 bg-white opacity-100;

}

.swiper-pagination-bullet.swiper-pagination-bullet-active{
    @apply rounded-xl w-6 bg-secondary;
}



</style>
