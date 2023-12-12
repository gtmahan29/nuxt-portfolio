<template>
    <div class="bg-[#f9f9f9] border border-white rounded-lg p-[30px] md:p-[40px] group hover:bg-[#0252CD] glass" >
        <div class="flex justify-center items-center bg-[#D4EDFF] text-primary-color w-[70px] h-[70px] leading-[70px] rounded-full text-center text-[40px] mb-[25px] transition duration-500 ease-in-out group-hover:scale-[1.1] group-hover:bg-white">
            <Icon :name=props.icon size="35" color="#0252CD"/>
        </div>
        <h3 class="text-lg mb-[15px] font-bold group-hover:text-white">{{ title }}</h3>
        <p class="group-hover:text-white text-sm">{{ desc }}</p>
    </div>
</template>

<script setup>
import { defineProps } from 'vue';

const props = defineProps(['title', 'desc', 'icon'])
</script>

<style lang="scss" scoped>

</style>