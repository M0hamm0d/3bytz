<script setup>
defineProps(['text', 'bg', 'color', 'pixel'])
</script>
<template>
  <button
    class="button"
    :style="{
      backgroundColor: `${bg}`,
      color: `${color}`,
      border: `${pixel} solid #060320`,
    }"
  >
    {{ text }}
  </button>
</template>
<style scoped>
.button {
  padding: 12px 16px;
  gap: 10px;
  border-radius: 1000px;
  opacity: 0px;
  cursor: pointer;
}
</style>
