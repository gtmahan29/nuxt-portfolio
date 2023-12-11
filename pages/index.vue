<template>
  <div class="mb-24 bg-[#f7f7f7]">
    <Hero />
  </div>
  <div class="services-section container mx-auto px-12 mb-24">
    <h2 class="text-[40px] text-center font-bold mb-12">What <span
        class="z-10 relative before:bg-secondary before:w-full before:bottom-2 before:h-3 before:absolute before:-z-10">Services</span>
      Do I Provide?</h2>
    <ul class="services grid grid-cols-4 gap-8 w-full">
      <li v-for="service in serviceDetails" :key="service.title" class="service">
        <Service :title="service.title" :desc="service.desc" :icon="service.icon" />
      </li>
    </ul>
  </div>

  <div class="skills-section container mx-auto px-12 mb-24">
    <Skills />
  </div>

  <div class="experience-section container mx-auto px-12 mb-24">
    <Experience />
  </div>

  <div class="projects-section container mx-auto px-12 mb-24">
    <h2 class="text-[40px] text-center font-bold mb-12"><span
        class="z-10 relative before:bg-secondary before:w-full before:bottom-2 before:h-3 before:absolute before:-z-10">Featured</span>
      Projects</h2>
    <ul class="projects flex gap-8 w-full">
      <li v-for="project in projects" :key="project.title" class="flex-1">
        <Project :title="project.title" :tags="project.tags" :background="project.background" :image="project.image" />
      </li>
    </ul>
  </div>

  <div class="testimonial-section mx-auto mb-16 bg-lightGray">
    <Testimonial />
  </div>

  <div class="contact-block-section container px-12 mx-auto">
    <ContactBlock />
  </div>
</template>

<script setup>
import { reactive } from 'vue'

const serviceDetails = reactive([
  {
    title: 'Web Development',
    desc: 'Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed.',
    icon: 'mdi:web',
  },
  {
    title: 'App Development',
    desc: 'Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed.',
    icon: 'circum:mobile-3',
  },
  {
    title: 'UI Design',
    desc: 'Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed.',
    icon: 'tdesign:logo-figma',
  },
  {
    title: 'Production',
    desc: 'Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed.',
    icon: 'fluent:production-checkmark-24-regular',
  },
])

const projects = reactive([
  {
    title: 'Bankist App',
    tags: 'JavaScript',
    image: '~/assets/img/Project.png',
  },
  {
    title: 'Admin Dashboard',
    tags: 'Vue.JS',
    image: '~/assets/img/Project.png',
  },
  {
    title: 'Portfolio',
    tags: 'Vue.JS',
    image: '~/assets/img/Project.png',
  },
])


</script>

<style lang="scss" scoped></style>