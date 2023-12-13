<template>
    <div class="testimonial container flex flex-col justify-center items-center text-center py-24 px-12 mx-auto relative">
        <h2 class="text-[40px] text-center font-bold mb-12">What <span
                class="z-10 relative before:bg-secondary before:w-full before:bottom-2 before:h-3 before:absolute before:-z-10">They
                Say</span> About Me</h2>
        <Swiper :modules="modules" :loop="true" :effect="'cards'" @swiper="onSwiper" @slideChange="onSlideChange"
            :cardsEffect='{
                "perSlideOffset": 12,
                "perSlideRotate": 4,
                "slideShadows": false
            }' class="w-1/2 flex gap-16 !p-0">
            <SwiperSlide
                class="bg-white/5 rounded-xl glass bg-none border-2 border-solid border-[#e9e9e9] !backdrop-blur-[25px] bg-opacity-10 py-8 px-16 shadow-[inset_0px_-4px_30px_0px_rgba(100,100,100,0.1)]">
                <div class="relative rounded-xl h-[16rem] truncate">
                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                    <p class="text-slate-400 whitespace-normal text-justify">"One disadvantage of Lorum Ipsum is that in
                        Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        "</p>
                    <ul class="list-none mb-0 text-amber-400 mt-3">
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                    </ul>
                </div>

                <div class="divider"></div>

                <div class="text-center mt-5 flex items-center gap-6">
                    <img src="~/assets/img/avatars/2.png" class="h-16 w-16 rounded-full" alt="">
                    <div class="flex flex-col items-start justify-center">
                        <h6 class="text-[18px] font-bold">Jemina Clone</h6>
                        <span class="text-slate-400 text-sm">Manager</span>
                    </div>
                </div>
            </SwiperSlide>
            <SwiperSlide
                class="bg-white/5 rounded-xl glass bg-none border-2 border-solid border-[#e9e9e9] !backdrop-blur-[25px] bg-opacity-10 py-8 px-16 shadow-[inset_0px_-4px_30px_0px_rgba(100,100,100,0.1)]">
                <div class="relative rounded-xl h-[16rem] truncate">
                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                    <p class="text-slate-400 whitespace-normal text-justify">"One disadvantage of Lorum Ipsum is that in
                        Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        "</p>
                    <ul class="list-none mb-0 text-amber-400 mt-3">
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                    </ul>
                </div>

                <div class="divider"></div>

                <div class="text-center mt-5 flex items-center gap-6">
                    <img src="~/assets/img/avatars/2.png" class="h-16 w-16 rounded-full" alt="">
                    <div class="flex flex-col items-start justify-center">
                        <h6 class="text-[18px] font-bold">Jemina Clone</h6>
                        <span class="text-slate-400 text-sm">Manager</span>
                    </div>
                </div>
            </SwiperSlide>
            <SwiperSlide
                class="bg-white/5 rounded-xl glass bg-none border-2 border-solid border-[#e9e9e9] !backdrop-blur-[25px] bg-opacity-10 py-8 px-16 shadow-[inset_0px_-4px_30px_0px_rgba(100,100,100,0.1)]">
                <div class="relative rounded-xl h-[16rem] truncate">
                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                    <p class="text-slate-400 whitespace-normal text-justify">"One disadvantage of Lorum Ipsum is that in
                        Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        "</p>
                    <ul class="list-none mb-0 text-amber-400 mt-3">
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                    </ul>
                </div>

                <div class="divider"></div>

                <div class="text-center mt-5 flex items-center gap-6">
                    <img src="~/assets/img/avatars/2.png" class="h-16 w-16 rounded-full" alt="">
                    <div class="flex flex-col items-start justify-center">
                        <h6 class="text-[18px] font-bold">Jemina Clone</h6>
                        <span class="text-slate-400 text-sm">Manager</span>
                    </div>
                </div>
            </SwiperSlide>
            <SwiperSlide
                class="bg-white/5 rounded-xl glass bg-none border-2 border-solid border-[#e9e9e9] !backdrop-blur-[25px] bg-opacity-10 py-8 px-16 shadow-[inset_0px_-4px_30px_0px_rgba(100,100,100,0.1)]">
                <div class="relative rounded-xl h-[16rem] truncate">
                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                    <p class="text-slate-400 whitespace-normal text-justify">"One disadvantage of Lorum Ipsum is that in
                        Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        "</p>
                    <ul class="list-none mb-0 text-amber-400 mt-3">
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                    </ul>
                </div>

                <div class="divider"></div>

                <div class="text-center mt-5 flex items-center gap-6">
                    <img src="~/assets/img/avatars/2.png" class="h-16 w-16 rounded-full" alt="">
                    <div class="flex flex-col items-start justify-center">
                        <h6 class="text-[18px] font-bold">Jemina Clone</h6>
                        <span class="text-slate-400 text-sm">Manager</span>
                    </div>
                </div>
            </SwiperSlide>
            <SwiperSlide
                class="bg-white/5 rounded-xl glass bg-none border-2 border-solid border-[#e9e9e9] !backdrop-blur-[25px] bg-opacity-10 py-8 px-16 shadow-[inset_0px_-4px_30px_0px_rgba(100,100,100,0.1)]">
                <div class="relative rounded-xl h-[16rem] truncate">
                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                    <p class="text-slate-400 whitespace-normal text-justify">"One disadvantage of Lorum Ipsum is that in
                        Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        "</p>
                    <ul class="list-none mb-0 text-amber-400 mt-3">
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                    </ul>
                </div>

                <div class="divider"></div>

                <div class="text-center mt-5 flex items-center gap-6">
                    <img src="~/assets/img/avatars/2.png" class="h-16 w-16 rounded-full" alt="">
                    <div class="flex flex-col items-start justify-center">
                        <h6 class="text-[18px] font-bold">Jemina Clone</h6>
                        <span class="text-slate-400 text-sm">Manager</span>
                    </div>
                </div>
            </SwiperSlide>
            <SwiperSlide
                class="bg-white/5 rounded-xl glass bg-none border-2 border-solid border-[#e9e9e9] !backdrop-blur-[25px] bg-opacity-10 py-8 px-16 shadow-[inset_0px_-4px_30px_0px_rgba(100,100,100,0.1)]">
                <div class="relative rounded-xl h-[16rem] truncate">
                    <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                    <p class="text-slate-400 whitespace-normal text-justify">"One disadvantage of Lorum Ipsum is that in
                        Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        appear more frequently than others.One disadvantage of Lorum Ipsum is that in Latin certain letters
                        "</p>
                    <ul class="list-none mb-0 text-amber-400 mt-3">
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                        <li class="inline"><i class="mdi mdi-star"></i></li>
                    </ul>
                </div>

                <div class="divider"></div>

                <div class="text-center mt-5 flex items-center gap-6">
                    <img src="~/assets/img/avatars/2.png" class="h-16 w-16 rounded-full" alt="">
                    <div class="flex flex-col items-start justify-center">
                        <h6 class="text-[18px] font-bold">Jemina Clone</h6>
                        <span class="text-slate-400 text-sm">Manager</span>
                    </div>
                </div>
            </SwiperSlide>
            
        </Swiper>
        <div class="absolute left-[25%] shadow-[0px_0px_100px_180px_rgba(255,244,204,0.2)] bg-orange-500 backdrop-blur-3xl">
        </div>
        <div
            class="absolute right-[30%] top-[80%] shadow-[0px_0px_100px_180px_rgba(255,244,204,0.3)] bg-orange-500 backdrop-blur-3xl">
        </div>
    </div>
</template>

<script setup>
import { Navigation, Pagination, Scrollbar, A11y, Autoplay, EffectCards, EffectCoverflow } from 'swiper/modules';
import 'swiper/css';
import 'swiper/css/navigation';
import 'swiper/css/pagination';
import 'swiper/css/scrollbar';
import 'swiper/scss/effect-coverflow';

const modules = [Navigation, Pagination, A11y, EffectCards, Autoplay, EffectCoverflow];

</script>


<style lang="scss" scoped></style>