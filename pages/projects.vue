<template>
    <div class="projects-sectio container mx-auto">
        <div class="text-center flex flex-col rounded-b-3xl mb-8 bg-primary text-white justify-center">
            <span class="text-white tracking-widest3x text-xs font-bold mb-10 mt-16">My PROJECTS</span>
            <div class="projects-title w-2/3 mx-auto mb-10">
                <span class="text-[66px] font-bold">
                    The Various Works That I Have Done <span class="z-10 relative  before:w-full before:bottom-2 before:h-7 before:absolute before:-z-10">Amazingly</span> 
                </span>
            </div>
            <p class="w-1/2 mx-auto mb-20">Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed. Ullamcorper tellus ac cras nec, pretium laoreet duis. </p>
        </div>
        <div class="projects-list px-12 mb-16">
            <ul class="Projects grid grid-cols-2 sm:grid-cols-1 md:grid-cols-2 justify-between gap-8 w-full">
                <li v-for="project in projects" :key="project.title" class="">
                    <Project :title="project.title" :tags="project.tags" :background="project.background" :image="project.image"/>
                </li>
            </ul>
        </div>
        <div class="px-12">
            <ContactBlock/>
        </div>
    </div>
</template>

<script setup>
const projects = reactive([
  {
    title: 'Bankist App',
    tags: 'JavaScript',
    background: 'project-bg-1',
    image: '~/assets/img/Project.png',
  },
  {
    title: 'Admin Dashboard',
    tags: 'Vue.JS',
    background: 'project-bg-2',
    image: '~/assets/img/Project.png',
  },
  {
    title: 'Portfolio',
    tags: 'Vue.JS',
    background: 'project-bg-3',
    image: '~/assets/img/Project.png',
  },
  {
    title: 'Portfolio',
    tags: 'Vue.JS',
    background: 'project-bg-3',
    image: '~/assets/img/Project.png',
  },
])
</script>

<style lang="scss" scoped>

</style>