<template>
    <div>
        <Swiper :modules=modules :slides-per-view="3" :loop="true" :effect="'creative'" pagination :autoplay="{
            delay: 8000,
            disableOnInteraction: true,
        }" @Swiper="onSwiper" @slideChange="onSlideChange"
            class="swiper header-swiper-cards h-40 w-4/5 max-w-full rounded-lg lg:w-60 swiper-cards swiper-3d swiper-initialized swiper-horizontal swiper-watch-progress"
            style="--swiper-theme-color:#fff">
            <SwiperSlide class="swiper-slide !flex items-center justify-center rounded-2xl font-bold text-white"
                style="background: rgb(206, 17, 17); width: 240px; z-index: 3; transform: translate3d(calc(0px + -13%), 0px, -200px) rotateZ(-4deg) scale(1); transition-duration: 0ms;"
                role="group" aria-label="1 / 5">
                Slide 1
                <div class="swiper-slide-shadow swiper-slide-shadow-cards"
                    style="opacity: 0; transition-duration: 0ms;"></div>
            </SwiperSlide>
            <SwiperSlide class="swiper-slide !flex items-center justify-center rounded-2xl font-bold text-white swiper-slide-prev"
                style="background: rgb(0, 140, 255); width: 240px; z-index: 4; transform: translate3d(calc(-240px + -7.25%), 0px, -100px) rotateZ(-2deg) scale(1); transition-duration: 0ms;"
                role="group" aria-label="2 / 5">
                Slide 2
                <div class="swiper-slide-shadow swiper-slide-shadow-cards"
                    style="opacity: 1; transition-duration: 0ms;"></div>
            </SwiperSlide>
            <SwiperSlide class="swiper-slide !flex items-center justify-center rounded-2xl font-bold text-white swiper-slide-visible swiper-slide-fully-visible swiper-slide-active"
                style="background: rgb(10, 184, 111); width: 240px; z-index: 5; transform: translate3d(-480px, 0px, 0px) rotateZ(0deg) scale(1); transition-duration: 0ms;"
                role="group" aria-label="3 / 5">
                Slide 3
                <div class="swiper-slide-shadow swiper-slide-shadow-cards"
                    style="opacity: 0; transition-duration: 0ms;"></div>
            </SwiperSlide>
            <SwiperSlide class="swiper-slide !flex items-center justify-center rounded-2xl font-bold text-white swiper-slide-next"
                style="background: rgb(211, 122, 7); width: 240px; z-index: 4; transform: translate3d(calc(-720px + 7.25%), 0px, -100px) rotateZ(2deg) scale(1); transition-duration: 0ms;"
                role="group" aria-label="4 / 5">
                Slide 4
                <div class="swiper-slide-shadow swiper-slide-shadow-cards"
                    style="opacity: 1; transition-duration: 0ms;"></div>
            </SwiperSlide>
            <SwiperSlide class="swiper-slide !flex items-center justify-center rounded-2xl font-bold text-white"
                style="background: rgb(118, 163, 12); width: 240px; z-index: 3; transform: translate3d(calc(-960px + 13%), 0px, -200px) rotateZ(4deg) scale(1); transition-duration: 0ms;"
                role="group" aria-label="5 / 5">
                Slide 5
                <div class="swiper-slide-shadow swiper-slide-shadow-cards"
                    style="opacity: 1; transition-duration: 0ms;"></div>
            </SwiperSlide>
            <SwiperPagination class="swiper-pagination swiper-pagination-bullets swiper-pagination-horizontal">
                <span class="swiper-pagination-bullet"></span>
                <span class="swiper-pagination-bullet"></span>
                <span class="swiper-pagination-bullet swiper-pagination-bullet-active" aria-current="true"></span>
                <span class="swiper-pagination-bullet"></span>
                <span class="swiper-pagination-bullet"></span>
            </SwiperPagination>
            <span class="swiper-notification" aria-live="assertive" aria-atomic="true"></span>
        </Swiper>
    </div>
</template>

<script setup>
import { Navigation, Pagination, Scrollbar, A11y } from 'swiper/modules';
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';
import 'swiper/css/navigation';
import 'swiper/css/pagination';
import 'swiper/css/scrollbar';

const onSwiper = (swiper) => {
    console.log(swiper);
};
const onSlideChange = () => {
    console.log('slide change');
};

const modules = [Navigation, Pagination, Scrollbar, A11y];
</script>

<style lang="scss" scoped></style>