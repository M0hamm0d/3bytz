<script setup>
import inTouch from '../assets/images/inTouch.png'
import getInTouch from '../assets/images/getInTouch.png'
import TheButton from './TheButtons.vue'
defineProps(['h1', 'text', 'btnText'])
</script>
<template>
  <div class="getInTouch">
    <img :src="inTouch" alt="" />
    <div class="overlay">
      <img :src="getInTouch" alt="" />
    </div>
    <div class="overlayText">
      <div class="top">
        <h1>{{ h1 }}</h1>
        <p>{{ text }}</p>
      </div>
      <div class="btn">
        <TheButton :text="btnText" bg="#fcfcfe" color="#060320" pixel="1px" />
      </div>
    </div>
  </div>
</template>
<style>
.getInTouch {
  position: relative;
}
.getInTouch img {
  width: 100%;
}
.overlay {
  position: absolute;
  inset: 0;
  opacity: 70%;
}
.top {
  display: flex;
  flex-direction: column;
  gap: 8px;
  align-items: center;
}
.top h1 {
  font-size: 28px;
}
.overlayText {
  position: absolute;
  inset: 0;
  color: white;
  display: flex;
  flex-direction: column;
  gap: 16px;
  align-items: center;
  justify-content: center;
}
.btn {
  display: flex;
  justify-content: center;
}
</style>
