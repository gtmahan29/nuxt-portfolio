<template>
    <div class="hero container rounded-b-3xl mx-auto px-12 flex h-full items-start justify-between pt-12 bg-[url('~/assets/img/pattern.png')] bg-no-repeat bg-[length:50rem] bg-[right_bottom_-10rem]">
        <div class="hero-content flex flex-col gap-6 justify-center items-start w-6/12 py-16">
            <span class="text-primary tracking-widest3x text-xs font-bold">HI, I AM MAHAN</span>
            <div class="hero-title flex flex-col">
                <span class="text-[46px] font-bold">
                    Proffesional 
                </span>
                <span class="text-[46px] font-bold">
                    Front-End
                </span>
                <span class="text-[46px] font-bold z-10">
                    Web Developer
                </span>
            </div>
            <p class="w-5/6 text-justify">Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed. Ullamcorper tellus ac cras nec, pretium laoreet duis. </p>
            <div class="btn-actions flex items-center gap-8">
                <button class="btn bg-primary rounded-full text-white text-xs capitalize px-8 hover:bg-blue-500">Contact Me</button>
                <div class="social-links flex gap-8">
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
        <div class="hero-image flex justify-center h-full w-6/12 mx-auto">
            <img src="~/assets/img/Hero-background3.png" alt="" class="relative">
        </div>
    </div>
</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>

</style>