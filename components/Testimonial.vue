<template>
    <div class="testimonial container flex flex-col justify-center items-center text-center py-24 px-12 mx-auto">
        <h2 class="text-[40px] text-center font-bold mb-12">What <span
                class="z-10 relative before:bg-secondary before:w-full before:bottom-2 before:h-3 before:absolute before:-z-10">They
                Say</span> About Me</h2>
        <!-- 
        <div class="carousel carousel-center w-1/2 flex text-center mb-8">
            <div id="item1" class="carousel-item w-full">
                Sapien pretium ut massa aliquet tellus pellentesque elementum. Pellentesque pellentesque in curabitur turpis sed dolor adipiscing mi. Gravida consequat ornare at dui gravida ut tortor. Nisi turpis in sed gravida nec vitae. Arcu, ut et integer bibendum duis lacus malesuada. In mi elementum mauris orci dictum sollicitudin odio duis. Vulputate egestas commodo nisl id mauris. Magnis elit ultricies aliquam adipiscing fames sed.
            </div> 
            <div id="item2" class="carousel-item w-full">
                Sapien pretium ut massa aliquet tellus pellentesque elementum. Pellentesque pellentesque in curabitur turpis sed dolor adipiscing mi. Gravida consequat ornare at dui gravida ut tortor. Nisi turpis in sed gravida nec vitae. Arcu, ut et integer bibendum duis lacus malesuada. In mi elementum mauris orci dictum sollicitudin odio duis. Vulputate egestas commodo nisl id mauris. Magnis elit ultricies aliquam adipiscing fames sed.2222222222222222222222222222
            </div> 
            <div id="item3" class="carousel-item w-full">
                Sapien pretium ut massa aliquet tellus pellentesque elementum. Pellentesque pellentesque in curabitur turpis sed dolor adipiscing mi. Gravida consequat ornare at dui gravida ut tortor. Nisi turpis in sed gravida nec vitae. Arcu, ut et integer bibendum duis lacus malesuada. In mi elementum mauris orci dictum sollicitudin odio duis. Vulputate egestas commodo nisl id mauris. Magnis elit ultricies aliquam adipiscing fames sed.33333333333333333333333333333
            </div> 
            <div id="item4" class="carousel-item w-full">
                Sapien pretium ut massa aliquet tellus pellentesque elementum. Pellentesque pellentesque in curabitur turpis sed dolor adipiscing mi. Gravida consequat ornare at dui gravida ut tortor. Nisi turpis in sed gravida nec vitae. Arcu, ut et integer bibendum duis lacus malesuada. In mi elementum mauris orci dictum sollicitudin odio duis. Vulputate egestas commodo nisl id mauris. Magnis elit ultricies aliquam adipiscing fames sed.444444444444444444
            </div>
            <div id="item5" class="carousel-item w-full">
                Sapien pretium ut massa aliquet tellus pellentesque elementum. Pellentesque pellentesque in curabitur turpis sed dolor adipiscing mi. Gravida consequat ornare at dui gravida ut tortor. Nisi turpis in sed gravida nec vitae. Arcu, ut et integer bibendum duis lacus malesuada. In mi elementum mauris orci dictum sollicitudin odio duis. Vulputate egestas commodo nisl id mauris. Magnis elit ultricies aliquam adipiscing fames sed.5555555555555555
            </div>
        </div>
        <div class="flex justify-center w-full py-2 gap-2">
            <a href="#item1" class="btn p-0 m-4 w-20 h-auto bg-transparent outline-none border-none hover:bg-transparent">
                <img src="~/assets/img/avatars/2.png" alt="">         
            </a> 
            <a href="#item2" class="btn p-0 m-4 w-20 h-auto bg-transparent outline-none border-none hover:bg-transparent">
                <img src="~/assets/img/avatars/2.png" alt=""> 
            </a> 
            <a href="#item3" class="btn p-0 m-4 w-20 h-auto bg-transparent outline-none border-none hover:bg-transparent">
                <img src="~/assets/img/avatars/2.png" alt="">
            </a> 
            <a href="#item4" class="btn p-0 m-4 w-20 h-auto bg-transparent outline-none border-none hover:bg-transparent">
                <img src="~/assets/img/avatars/2.png" alt="">
            </a>
            <a href="#item5" class="btn p-0 m-4 w-20 h-auto bg-transparent outline-none border-none hover:bg-transparent">
                <img src="~/assets/img/avatars/2.png" alt="">
            </a>
        </div> -->
        <Swiper :modules=modules :slides-per-view="3" :loop="true" :effect="'creative'" autoplay class="max-w-screen-xl flex gap-16">
            <SwiperSlide class="">
                <div class="text-center">
                    <div class="cursor-e-resize">
                        <div
                            class="relative h-[15rem] rounded-xl m-4 p-6 bg-white before:content-[''] before:absolute before:start-1/2 before:-bottom-[4px] before:box-border before:border-8 before:rotate-[45deg] before:border-t-transparent before:border-e-white before:border-b-white before:border-s-transparent dark:before:shadow-gray-700 before:origin-top-left">
                            <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                            <p class="text-slate-400">"One disadvantage of Lorum Ipsum is that in Latin certain letters
                                appear more frequently than others."</p>
                            <ul class="list-none mb-0 text-amber-400 mt-3">
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                            </ul>
                        </div>

                        <div class="text-center mt-5">
                            <img src="~/assets/img/avatars/2.png" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                            <h6 class="mt-2 font-semibold">Jemina Clone</h6>
                            <span class="text-slate-400 text-sm">Manager</span>
                        </div>
                    </div>
                </div>
            </SwiperSlide>
            <SwiperSlide class="">
                <div class="text-center">
                    <div class="cursor-e-resize">
                        <div
                            class="relative h-[15rem] rounded-xl m-4 p-6 bg-white before:content-[''] before:absolute before:start-1/2 before:-bottom-[4px] before:box-border before:border-8 before:rotate-[45deg] before:border-t-transparent before:border-e-white before:border-b-white before:border-s-transparent dark:before:shadow-gray-700 before:origin-top-left">
                            <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                            <p class="text-slate-400">"One disadvantage of Lorum Ipsum is that in Latin certain letters
                                appear more frequently than others."</p>
                            <ul class="list-none mb-0 text-amber-400 mt-3">
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                            </ul>
                        </div>

                        <div class="text-center mt-5">
                            <img src="~/assets/img/avatars/2.png" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                            <h6 class="mt-2 font-semibold">Jemina Clone</h6>
                            <span class="text-slate-400 text-sm">Manager</span>
                        </div>
                    </div>
                </div>
            </SwiperSlide>
            <SwiperSlide class="">
                <div class="text-center">
                    <div class="cursor-e-resize">
                        <div
                            class="relative h-[15rem] rounded-xl m-4 p-6 bg-white before:content-[''] before:absolute before:start-1/2 before:-bottom-[4px] before:box-border before:border-8 before:rotate-[45deg] before:border-t-transparent before:border-e-white before:border-b-white before:border-s-transparent dark:before:shadow-gray-700 before:origin-top-left">
                            <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                            <p class="text-slate-400">"One disadvantage of Lorum Ipsum is that in Latin certain letters
                                appear more frequently than others."</p>
                            <ul class="list-none mb-0 text-amber-400 mt-3">
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                            </ul>
                        </div>

                        <div class="text-center mt-5">
                            <img src="~/assets/img/avatars/2.png" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                            <h6 class="mt-2 font-semibold">Jemina Clone</h6>
                            <span class="text-slate-400 text-sm">Manager</span>
                        </div>
                    </div>
                </div>
            </SwiperSlide>
            <SwiperSlide class="">
                <div class="text-center">
                    <div class="cursor-e-resize">
                        <div
                            class="relative h-[15rem] rounded-xl m-4 p-6 bg-white before:content-[''] before:absolute before:start-1/2 before:-bottom-[4px] before:box-border before:border-8 before:rotate-[45deg] before:border-t-transparent before:border-e-white before:border-b-white before:border-s-transparent dark:before:shadow-gray-700 before:origin-top-left">
                            <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                            <p class="text-slate-400">"One disadvantage of Lorum Ipsum is that in Latin certain letters
                                appear more frequently than others."</p>
                            <ul class="list-none mb-0 text-amber-400 mt-3">
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                            </ul>
                        </div>

                        <div class="text-center mt-5">
                            <img src="~/assets/img/avatars/2.png" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                            <h6 class="mt-2 font-semibold">Jemina Clone</h6>
                            <span class="text-slate-400 text-sm">Manager</span>
                        </div>
                    </div>
                </div>
            </SwiperSlide>
            <SwiperSlide class="">
                <div class="text-center">
                    <div class="cursor-e-resize">
                        <div
                            class="relative h-[15rem] rounded-xl m-4 p-6 bg-white before:content-[''] before:absolute before:start-1/2 before:-bottom-[4px] before:box-border before:border-8 before:rotate-[45deg] before:border-t-transparent before:border-e-white before:border-b-white before:border-s-transparent dark:before:shadow-gray-700 before:origin-top-left">
                            <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                            <p class="text-slate-400">"One disadvantage of Lorum Ipsum is that in Latin certain letters
                                appear more frequently than others."</p>
                            <ul class="list-none mb-0 text-amber-400 mt-3">
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                            </ul>
                        </div>

                        <div class="text-center mt-5">
                            <img src="~/assets/img/avatars/2.png" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                            <h6 class="mt-2 font-semibold">Jemina Clone</h6>
                            <span class="text-slate-400 text-sm">Manager</span>
                        </div>
                    </div>
                </div>
            </SwiperSlide>
            <SwiperSlide class="">
                <div class="text-center">
                    <div class="cursor-e-resize">
                        <div
                            class="relative h-[15rem] rounded-xl m-4 p-6 bg-white before:content-[''] before:absolute before:start-1/2 before:-bottom-[4px] before:box-border before:border-8 before:rotate-[45deg] before:border-t-transparent before:border-e-white before:border-b-white before:border-s-transparent dark:before:shadow-gray-700 before:origin-top-left">
                            <i class="mdi mdi-format-quote-open mdi-48px text-indigo-600"></i>
                            <p class="text-slate-400">"One disadvantage of Lorum Ipsum is that in Latin certain letters
                                appear more frequently than others."</p>
                            <ul class="list-none mb-0 text-amber-400 mt-3">
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                                <li class="inline"><i class="mdi mdi-star"></i></li>
                            </ul>
                        </div>

                        <div class="text-center mt-5">
                            <img src="~/assets/img/avatars/2.png" class="h-14 w-14 rounded-full shadow-md mx-auto" alt="">
                            <h6 class="mt-2 font-semibold">Jemina Clone</h6>
                            <span class="text-slate-400 text-sm">Manager</span>
                        </div>
                    </div>
                </div>
            </SwiperSlide>
            
        </Swiper>
    </div>
</template>

<script setup>
import { Navigation, Pagination, Scrollbar, A11y, Autoplay } from 'swiper/modules';
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';
import 'swiper/css/navigation';
import 'swiper/css/pagination';
import 'swiper/css/scrollbar';

const modules = [Navigation, Pagination, Scrollbar, A11y, Autoplay];

</script>

<style lang="scss" scoped></style>