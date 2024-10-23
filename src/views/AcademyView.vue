<script setup>
import AcademyHeroImg from '../assets/images/academyHeroImg.png'
import TheButton from '@/components/TheButtons.vue'
import TheReviews from '@/components/TheReviews.vue'
</script>
<template>
  <div class="container">
    <div class="heroSection">
      <div class="main-hero">
        <div class="hero-text">
          <h1>
            Join Our Training and Start Providing Tech Solutions,
            <span>One Byte</span> at a Time
          </h1>
          <p>
            We provide a variety of courses for kids and adults, aimed at
            helping you reach your goals.
          </p>
          <div class="hero-nav-btn">
            <TheButton
              text="Start Learning"
              bg="#005CC9"
              color="#fff"
              pixel="0px"
            />
            <TheButton
              text="View Courses"
              bg="#fcfcfe"
              color="#060320"
              pixel="1px"
            />
          </div>
          <TheReviews justify="flex-start" />
        </div>
        <div class="heroImg">
          <img :src="AcademyHeroImg" alt="" />
        </div>
      </div>
      <div class="view-courses">
        <p>View our courses</p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.heroSection {
  display: flex;
  flex-direction: column;
  gap: 64px;
}
.main-hero {
  padding: 50px 100px 50px 100px;
  display: flex;
  justify-content: space-between;
  gap: 16px;
  align-items: center;
}
.hero-text {
  display: flex;
  flex-direction: column;
  gap: 32px;
  max-width: 640px;
}
.hero-text h1 {
  font-size: 48px;
  line-height: 55px;
  font-weight: 600;
}
.hero-text h1 span {
  color: #005cc9;
}
.hero-nav-btn {
  display: flex;
  gap: 16px;
}
.heroImg img {
  width: 100%;
}
</style>
