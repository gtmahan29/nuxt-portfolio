<template>
    <div class="navbar sticky top-0 z-50 transition-colors duration-75 w-full bg-opacity-60 backdrop-filter backdrop-blur-md flex items-center" :class="scrollPosition === 0 ? 'bg-lightGray shadow-none' : 'bg-white'">
        <div class="container mx-auto px-12 py-4">
            <div class="navbar-start inline-block">
                <div class="dropdown">
                    <div class="w-12">
                        <NuxtLink to="/">
                            <img src="~/assets/img/Logo.png" alt="">
                        </NuxtLink>
                    </div>
                </div>
            </div>
            <div class="navbar-center mx-auto hidden lg:flex">
                <ul class="menu menu-horizontal px-1 text-md font-bold text-gray tracking-tighter">
                    <li class="hover:text-black">
                        <NuxtLink to="/" class="tracking-wide hover:bg-transparent">
                            Home
                        </NuxtLink>
                    </li>
                    <li class="hover:text-black bg-transparent">
                        <NuxtLink to="/projects" class="tracking-wide hover:bg-transparent">
                            Projects
                        </NuxtLink>
                    </li>
                    <li class="hover:text-black bg-transparent">
                        <NuxtLink to="/about" class="tracking-wide hover:bg-transparent">
                            About Me
                        </NuxtLink>
                    </li>
                    <li class="hover:text-black bg-transparent">
                        <NuxtLink to="/contacts" class="tracking-wide hover:bg-transparent">
                            Contact Me
                        </NuxtLink>
                    </li>
                </ul>
            </div>
            <div class="navbar-end flex">
                <button class="btn btn-outline border-gray rounded-full text-xs px-8">
                    Get in touch
                </button>
            </div>
        </div>
    </div>
</template>

<script setup>
import { ref, onMounted } from 'vue';

const scrollPosition = ref(0);

function handleScroll() {
    scrollPosition.value = window.scrollY;
};

onMounted(() => {
    window.addEventListener('scroll', handleScroll)
});

</script>

<style lang="scss" scoped>

</style>