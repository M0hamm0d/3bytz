<script setup>
defineProps(['faq'])
const emit = defineEmits(['toggleAnswer'])
const handleClick = id => emit('toggleAnswer', id)
</script>
<template>
  <div class="faq">
    <div class="header" @click="() => handleClick(faq.id)">
      <div class="question">
        {{ faq.question }}
      </div>
      <div :class="['icon', { open: faq.isOpen }]">
        +
        <!-- <img src="" alt="" /> -->
      </div>
    </div>
    <!-- <div :class="['answer', { open: faq.isOpen }]">
      <p>{{ faq.answer }}</p>
    </div> -->
    <Transition>
      <div v-if="faq.isOpen" :class="['answer', { open: faq.isOpen }]">
        <p>{{ faq.answer }}</p>
      </div>
    </Transition>
  </div>
</template>
<style scoped>
.faq {
  /* padding: 12px; */
  padding: 0 16px;
  display: flex;
  flex-direction: column;
  /* transition: 0.25s; */
  /* gap: 16px; */
  flex-grow: 1;
  border: 1px solid #e2e2e5;
  border-radius: 8px;
  background: #fcfcfc;
  justify-content: center;
}
.header {
  display: flex;
  justify-content: space-between;
  font-weight: 700;
  padding: 16px 0;
  cursor: pointer;
  width: 100%;
}
.header .open {
  transform: rotate(30deg);
  transition: 3s;
}
.question {
  font-weight: 700;
  /* transition: 0.25s; */
}
.answer {
  height: 0;
  overflow: hidden;
}
.answer.open {
  padding: 0 0px 16px;
  overflow: visible;
  height: 100%;
}

.v-enter-active {
  transition: opacity 0.5s ease;
}

.v-enter-from,
.v-leave-to {
  opacity: 0;
}
</style>
