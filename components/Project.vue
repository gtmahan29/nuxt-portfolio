<template>
    <div class="bg-[#f9f9f9] border-white duration-500 rounded-lg glass bg-none hover:bg-white hover:dark:bg-slate-900 group">
        <div class="flex justify-center items-center p-8">
            <img src="~/assets/img/Project.png" alt="" class="w-4/6">
        </div>

        <div class="content mt-7 px-6 py-10">
            <a href="#" class="title h5 text-lg font-medium hover:text-indigo-600 group-hover:text-white">Plagiarism checker</a>
            <p class="text-slate-400 mt-3">The phrasal sequence of the is now so that many campaign and benefit</p>

            <div class="mt-5">
            <a href="#" class="relative inline-block font-semibold tracking-wide align-middle text-base text-center border-none after:content-[''] after:absolute after:h-px after:w-0 hover:after:w-full after:end-0 hover:after:end-auto after:bottom-0 after:start-0 after:duration-500 text-indigo-600 group-hover:text-white hover:after:bg-white duration-500 ease-in-out">Read More <i class="uil uil-arrow-right"></i></a>
            </div>
        </div>
    </div>
</template>

<script setup>
import { defineProps } from 'vue';

const props = defineProps(['title', 'tags', 'background', 'image'])
</script>

<style lang="scss" scoped>

</style>