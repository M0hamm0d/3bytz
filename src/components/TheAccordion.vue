<script setup>
import TheFaq from './TheFaq.vue'
import { ref } from 'vue'
const data = [
  {
    id: 1,
    question: 'What is the capital of Australia?',
    answer:
      'We offer software development, digital skills training, brand strategy, creative design, marketing solutions, tech optimization, and IT support.',
    isOpen: false,
  },
  {
    id: 2,
    question: 'What is the tallest animal on earth?',
    answer:
      'We offer software development, digital skills training, brand strategy, creative design, marketing solutions, tech optimization, and IT support.',
    isOpen: false,
  },
  {
    id: 3,
    question: 'What is the largest country in the world by area?',
    answer:
      'We offer software development, digital skills training, brand strategy, creative design, marketing solutions, tech optimization, and IT support.',
    isOpen: false,
  },
  {
    id: 4,
    question: 'What is the largest animal on earth?',
    answer:
      'We offer software development, digital skills training, brand strategy, creative design, marketing solutions, tech optimization, and IT support..',
    isOpen: false,
  },
]
const faqs = ref(data)
const toggleAnswer = id => {
  faqs.value = faqs.value.map(faq =>
    faq.isOpen && faq.id !== id ? { ...faq, isOpen: false } : faq,
  )
  faqs.value = faqs.value.map(faq =>
    faq.id === id ? { ...faq, isOpen: !faq.isOpen } : faq,
  )
}
</script>
<template>
  <main class="">
    <div class="faqs">
      <TheFaq
        v-for="faq in faqs"
        :key="faq.id"
        :faq="faq"
        @toggle-answer="toggleAnswer"
      />
    </div>
  </main>
</template>
<style scoped>
.faqs {
  display: flex;
  flex-direction: column;
  gap: 16px;
}
</style>
