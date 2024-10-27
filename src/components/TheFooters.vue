<script setup>
import emailSvg from '../assets/images/email-svg.png'
import logo from '../assets/images/3bytzLogo.png'
import twLogo from '../assets/images/Tw.png'
import fbLogo from '../assets/images/Fb.png'
import igLogo from '../assets/images/Ig.png'
import lnLogo from '../assets/images/Ln.png'
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
    <div class="our-social-container">
      <div class="ourSocials">
        <div class="logo">
          <img :src="logo" alt="" />
        </div>
        <div class="socialAccounts">
          <div class="email">
            Contact <a href="mailto:info@3bytz.com">info@3bytz.com</a>
          </div>
          <div class="socialPages">
            <p class="follow">Follow Us</p>
            <div class="socialLogos">
              <a href="#">
                <img :src="fbLogo" alt="" />
              </a>
              <a href="#">
                <img :src="twLogo" alt="" />
              </a>
              <a href="#">
                <img :src="igLogo" alt="" />
              </a>
              <a href="#">
                <img :src="lnLogo" alt="" />
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="copyrightSection">
        <div class="privacy">
          <p>Privacy Policy</p>
          <p>Terms of Use</p>
        </div>
        <div class="copyright">
          © 2023 . Powered by <span>3bytz</span>. All Rights Reserved.
        </div>
      </div>
      <div class="socialAccountsMobile">
        <div class="email">
          Contact <a href="mailto:info@3bytz.com">info@3bytz.com</a>
        </div>
        <div class="socialPages">
          <p class="follow">Follow Us</p>
          <div class="socialLogos">
            <a href="#">
              <img :src="fbLogo" alt="" />
            </a>
            <a href="#">
              <img :src="twLogo" alt="" />
            </a>
            <a href="#">
              <img :src="igLogo" alt="" />
            </a>
            <a href="#">
              <img :src="lnLogo" alt="" />
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<style scoped>
.footer {
  padding: 56px 40px 56px 40px;
  gap: 64px;
  display: flex;
  flex-direction: column;
  opacity: 0px;
  background: #fbfcff;
  font-family: Inter;
}
.our-social-container {
  display: flex;
  flex-direction: column;
  gap: 64px;
}
.newsletterSubscribe {
  display: flex;
  flex-direction: column;
  gap: 32px;
}
.subReason {
  max-width: 384px;
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
  max-width: 462px;
  margin: auto;
}
.input {
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
.socialAccounts {
  display: flex;
  gap: 56px;
  align-items: center;
}
.socialPages {
  display: flex;
  gap: 8px;
  align-items: center;
}
.socialLogos {
  display: flex;
  gap: 8px;
  align-items: center;
}
.follow {
  font-family: Inter;
}
.copyrightSection {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.privacy {
  display: flex;
  gap: 64px;
  align-items: center;
  font-family: Inter;
}
.privacy > p {
  font-family: Inter;
}
.copyright {
  font-family: Inter;
  color: #46464d;
}
.socialAccountsMobile {
  display: none;
}
@media screen and (max-width: 640px) {
  .footer {
    padding: 56px 24px 56px 24px;
  }
  .ourSocials {
    justify-content: center;
  }
  .logo {
    display: flex;
    justify-content: center;
  }
  .socialAccounts {
    display: none;
  }
  .copyrightSection {
    flex-direction: column;
    font-size: 12px;
  }
  .privacy {
    flex-direction: column;
    gap: 8px;
  }
  .our-social-container {
    gap: 16px;
  }
  .copyrightSection {
    gap: 8px;
  }
  .socialAccountsMobile {
    display: flex;
    font-size: 12px;
    align-items: center;
    justify-content: space-between;
  }
}
</style>
