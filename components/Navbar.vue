<template>
    <div class="navbar sticky top-0 z-50 transition-colors duration-75 w-full bg-opacity-80 backdrop-filter backdrop-blur-md flex items-center">
        <div class="container mx-auto px-12 py-4">
            <div class="navbar-start">
                <div class="w-12 flex items-center">
                    <NuxtLink to="/">
                        <img src="~/assets/img/Logo.png" alt="">
                    </NuxtLink>
                </div>
            </div>
            <div class="navbar-center mx-auto hidden lg:flex">
                <div class="dropdown">
                    <ul class="menu menu-horizontal px-1 text-sm font-bold text-gray tracking-tighter">
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