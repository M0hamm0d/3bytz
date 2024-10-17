<script setup>
import { RouterView } from 'vue-router'
import TheHeader from './components/TheHeader.vue'
import AboutUsHeader from './components/AboutUsHeader.vue'
import AcademyHeader from './components/AcademyHeader.vue'
import TheFooters from './components/TheFooters.vue'
</script>

<template>
  <div class="wrapper">
    <div class="" v-if="$route.path === '/about' || $route.path === '/project'">
      <AboutUsHeader />
    </div>
    <div class="" v-if="$route.path === '/' || $route.path === '/contact'">
      <TheHeader />
    </div>
    <div class="" v-if="$route.path === '/academy'">
      <AcademyHeader />
    </div>
  </div>
  <RouterView />
  <TheFooters />
</template>

<style scoped></style>
