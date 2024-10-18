<script setup>
import emailSvg from '../assets/images/email-svg.png'
import logo from '../assets/images/3bytzLogo.png'
</script>
<template>
  <footer class="footer">
    <div class="newsletterSubscribe">
      <div class="subReason">
        <h1>Subscribe to our newsletter</h1>
        <p>
          Never miss a beat. <br />
          Get a weekly dose of design inspiration, secrets, tips, trends, and
          banter in your inbox.
        </p>
      </div>
      <div class="subSection">
        <div class="input">
          <img :src="emailSvg" alt="" />
          <input type="text" placeholder="Email address" />
        </div>
        <button class="subscribe">Subscribe</button>
      </div>
    </div>
    <div class="ourSocials">
      <div class="logo">
        <img :src="logo" alt="" />
      </div>
      <div class="socialAccounts">
        <div class="email">Contact <a href="#">info@3bytz.com</a></div>
      </div>
    </div>
  </footer>
</template>
<style scoped>
.footer {
  padding: 56px 40px 56px 40px;
  gap: 64px;
  opacity: 0px;
  background: #fbfcff;
  font-family: Inter;
}
.newsletterSubscribe {
  display: flex;
  flex-direction: column;
  gap: 32px;
}
.subReason {
  width: 384px;
  margin: auto;
  display: flex;
  flex-direction: column;
  gap: 12px;
}
.subReason h1 {
  font-weight: 700;
  font-size: 24px;
  line-height: 28.8px;
  text-align: center;
  font-family: Inter;
}
.subReason p {
  font-family: Inter;
  font-size: 14px;
  font-weight: 400;
  line-height: 20.3px;
  text-align: center;
}
.subSection {
  display: flex;
  justify-content: center;
  gap: 16px;
  width: 462px;
  margin: auto;
}
.input {
  /* width: 319px; */
  height: 40px;
  display: flex;
  flex: 1;
  align-items: center;
  gap: 12px;
  border-radius: 6px;
  padding: 0 16px;
  border: 1px solid #d0d5dd;
}
.input input {
  width: 100%;
  height: 100%;
  outline: none;
  border: none;
  border-radius: 6px;
}
.subscribe {
  background-color: #005cc9;
  border-radius: 8px;
  padding: 0px 24px;
  border: none;
  color: white;
  height: 40px;
}
.logo img {
  width: 63.95px;
  height: 25px;
}
.ourSocials {
  display: flex;
  justify-content: space-between;
}
.socialAccounts {
  font-family: Inter;
}
.email {
  font-family: Inter;
}
</style>
