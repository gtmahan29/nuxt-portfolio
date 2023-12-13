<template>
    <div class="hero container rounded-b-3xl flex flex-wrap mx-auto px-12 h-full justify-between pt-12 bg-[url('~/assets/img/pattern.png')] bg-no-repeat bg-[length:50rem] bg-[right_bottom_-10rem]">
        <div class="hero-content flex flex-col sm:basis-full max-lg:mb-8 lg:basis-1/2 gap-6 justify-center md:items-center lg:items-start z-30">
            <span class="text-primary tracking-widest3x text-xs font-bold">HI, I AM MAHAN</span>
            <div class="hero-title flex flex-col">
                <span class="sm:text-center lg:text-start text-[46px] font-bold">
                    Proffesional 
                </span>
                <span class="sm:text-center lg:text-start text-[46px] font-bold">
                    Front-End
                </span>
                <span class="sm:text-center lg:text-start text-[46px] font-bold z-10">
                    Web Developer
                </span>
            </div>
            <p class="w-5/6 text-justify sm:text-center lg:text-start">Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed. Ullamcorper tellus ac cras nec, pretium laoreet duis. </p>
            <div class="btn-actions flex sm:flex-wrap lg:flex-nowrap sm:justify-center lg:justify-normal items-center gap-8">
                <button class="btn bg-primary rounded-full justify-center text-white text-sm capitalize px-8 hover:bg-blue-500">Contact Me</button>
                <div class="social-links flex justify-center gap-8 sm:basis-full max-lg:hidden">
                    <a href="#" class="text-3xl text-gray hover:text-black transition duration-300">
                        <Icon name="ri:instagram-fill" size="35" />
                    </a>
                    <a href="#" class="text-3xl text-gray hover:text-black transition duration-300">
                        <Icon name="simple-icons:telegram" />
                    </a>
                    <a href="#" class="text-3xl text-gray hover:text-black transition duration-300">
                        <Icon name="ion:logo-linkedin" />
                    </a>
                </div>
            </div>
        </div>
        <div class="hero-image flex sm:basis-full lg:basis-1/2 justify-center h-full mx-auto">
            <img src="~/assets/img/Hero-background3.png" alt="" class="relative w-[35rem]">
            <div class="absolute w-[8rem] -translate-x-1/2 -translate-y-1/2 ease-out" :style="{left: `${x}px`, top:`${y}px`}">
                <img src="~/assets/img/mouse-effect.png" alt="">
            </div>
        </div>
    </div>
</template>

<script setup>
// const { x, y } = useMouse();

</script>

<style lang="scss" scoped>

</style>