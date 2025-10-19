<template>
  <div class="bg-gray-100 text-center mb-10 py-10 relative">
    <h2 class="text-3xl font-bold mb-5">Testimonials</h2>
    <p class="text-gray-600 mb-10 max-w-2xl mx-auto">
      Nulla quis curabitur velit volutpat auctor bibendum consectetur sit.
    </p>

   <!-- Tugmalar (chetlarda) -->
<div
  class="swiper-button-prev absolute top-1/2 left-5 -translate-y-1/2 bg-white w-8 h-8 flex items-center justify-center rounded-full shadow cursor-pointer hover:bg-gray-200 transition"
>
</div>

<div
  class="swiper-button-next absolute top-1/2 right-5 -translate-y-1/2 bg-white w-8 h-8 flex items-center justify-center rounded-full shadow cursor-pointer hover:bg-gray-200 transition"
>
</div>


    <Swiper
      :modules="[Navigation, Autoplay]"
      :slides-per-view="1"
      :space-between="20"
      :navigation="{
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev'
      }"
      :autoplay="{ delay: 3000 }"
      loop
      :breakpoints="{
        768: { slidesPerView: 2 },
        1024: { slidesPerView: 3 }
      }"
      class="max-w-5xl mx-auto"
    >
      <SwiperSlide v-for="value in 5" :key="value">
        <TestimonialsItem />
      </SwiperSlide>
    </Swiper>
  </div>
</template>

<script setup>
import { Swiper, SwiperSlide } from 'swiper/vue'
import { Navigation, Autoplay } from 'swiper/modules'
import TestimonialsItem from '~/components/TestimonialsItem.vue'
</script>
