<script setup>
import hero1 from '../assets/images/hero1.png'
import hero2 from '../assets/images/hero2.png'
import hero3 from '../assets/images/hero3.png'
import hero4 from '../assets/images/hero4.png'
import reviewStars from '../assets/images/reviewStars.png'
defineProps(['justify'])
</script>
<template>
  <div
    class="reviews"
    :style="{
      justifyContent: `${justify}`,
    }"
  >
    <div class="reviewFaces">
      <img :src="hero1" alt="" />
      <img :src="hero2" alt="" />
      <img :src="hero3" alt="" />
      <img :src="hero4" alt="" />
    </div>
    <div class="reviewStars">
      <img :src="reviewStars" alt="" />
      <p>from 300+ reviews</p>
    </div>
  </div>
</template>
<style scoped>
.reviews {
  display: flex;
  gap: 5px;
}
.reviewStars {
  display: flex;
  flex-direction: column;
  gap: 3px;
}
</style>
