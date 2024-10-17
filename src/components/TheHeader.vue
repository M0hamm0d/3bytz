<script setup>
import { RouterLink } from 'vue-router'
import logo from '../assets/images/3bytzLogo.png'
import TheButton from '../components/TheButtons.vue'
</script>
<template>
  <header class="header">
    <div class="logo">
      <RouterLink to="/">
        <img :src="logo" alt="" />
      </RouterLink>
    </div>
    <div class="navigation">
      <RouterLink to="/about">About Us</RouterLink>
      <RouterLink to="">Service</RouterLink>
      <RouterLink to="/academy">Academy</RouterLink>
    </div>
    <div class="header-btn">
      <TheButton text="Our Services" bg="#fcfcfe" color="#060320" pixel="1px" />
      <TheButton text="Get Started" bg="#005CC9" color="#fff" pixel="0px" />
    </div>
  </header>
</template>
<style scoped>
.header {
  padding: 24px 100px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: #fbfcff;
  border-bottom: 1px solid #f0eded;
}
.logo img {
  width: 110px;
  height: 43px;
}
.navigation {
  display: flex;
  gap: 16px;
}
.navigation a {
  text-decoration: none;
}
.header-btn {
  display: flex;
  gap: 16px;
}
</style>
