<script setup>
import TheButton from '../components/TheButtons.vue'
import heroImg from '../assets/images/heroImg.png'
import hero1 from '../assets/images/hero1.png'
import hero2 from '../assets/images/hero2.png'
import hero3 from '../assets/images/hero3.png'
import hero4 from '../assets/images/hero4.png'
import reviewStars from '../assets/images/reviewStars.png'
</script>

<template>
  <div class="container">
    <div class="heroSection">
      <div class="techSolutionContainer">
        <div class="techSolution">
          <div class="reviews">
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
          <h1>
            Providing Tech Solutions By Pushing <span>One Byte</span> at a time
          </h1>
          <p>
            We deliver high-quality, versatile, and scalable software solutions
          </p>
        </div>
        <div class="heroNavBtn">
          <TheButton
            text="Get a Free Consultation"
            bg="#005CC9"
            color="#fff"
            pixel="0px"
          />
          <TheButton
            text="Explore Our Services"
            bg="#fcfcfe"
            color="#060320"
            pixel="1px"
          />
        </div>
      </div>
      <div class="heroImg">
        <img :src="heroImg" alt="" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.heroSection {
  padding: 50px 100px 50px 100px;
  display: flex;
  flex-direction: column;
  gap: 64px;
}
.techSolutionContainer {
  display: flex;
  flex-direction: column;
  gap: 32px;
}
.techSolution {
  display: flex;
  flex-direction: column;
  gap: 12px;
  max-width: 1021px;
  margin: 0 auto;
}
.reviews {
  display: flex;
  gap: 5px;
  justify-content: center;
}
.reviewStars {
  display: flex;
  flex-direction: column;
  gap: 3px;
}
.techSolution h1 {
  font-size: 51px;
  text-align: center;
  margin-bottom: 4px;
}
.techSolution h1 span {
  color: #005cc9;
}
.techSolution p {
  text-align: center;
}
.heroNavBtn {
  display: flex;
  justify-content: center;
  gap: 16px;
}
.heroImg img {
  width: 100%;
  height: auto;
}
</style>
