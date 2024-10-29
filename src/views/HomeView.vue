<script setup>
import TheButton from '../components/TheButtons.vue'
import TheAccordion from '@/components/TheAccordion.vue'
import heroImg from '../assets/images/heroImg.png'
import transistor from '../assets/images/transistor.png'
import statamic from '../assets/images/statamic.png'
import savvycal from '../assets/images/savvycal.png'
import tuple from '../assets/images/tuple.png'
import reform from '../assets/images/reform.png'
import adsClick from '../assets/images/ads_click.png'
import arrowRight from '../assets/images/arrow-right.png'
import readyToServe1 from '../assets/images/ready-to-serve-1.png'
import readyToServe2 from '../assets/images/ready-to-serve-2.png'
import readyToServe3 from '../assets/images/ready-to-serve-3.png'
import readyToServe4 from '../assets/images/ready-to-serve-4.png'
import innovation from '../assets/images/innivation.png'
import versatility from '../assets/images/versatility.png'
import excellence from '../assets/images/excellence.png'
import integrity from '../assets/images/integrity.png'
import collaboration from '../assets/images/collaboration.png'
import GetInTouch from '@/components/GetInTouch.vue'
import TheReviews from '@/components/TheReviews.vue'
</script>

<template>
  <div class="container">
    <div class="heroSection">
      <div class="techSolutionContainer">
        <div class="techSolution">
          <TheReviews justify="center" />
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
    <div class="ourTrusteeContainer">
      <div class="ourTrustee">
        <h3>Trusted by the world’s most innovative teams</h3>
        <div class="companyNumber">
          <p>Over 2500 companies use our tools to better their business.</p>
          <div class="customerStory">
            <p>Read our customer stories</p>
            <img :src="arrowRight" alt="" />
          </div>
        </div>
      </div>
      <div class="trustedBankLogo">
        <img :src="transistor" alt="" />
        <img :src="statamic" alt="" />
        <img :src="savvycal" alt="" />
        <img :src="tuple" alt="" />
        <img :src="reform" alt="" />
      </div>
    </div>
    <div class="aboutUsContainer">
      <div class="aboutUs">
        <h1>About Us</h1>
        <p>
          3bytz Solutions is a forward-thinking tech startup dedicated to
          solving societal challenges through innovative technological
          solutions. We are a tech startup passionate about using technology to
          address real-world problems. We identify societal challenges and
          develop innovative software solutions to create a positive impact.
        </p>
      </div>
      <div class="mission">
        <img :src="adsClick" alt="" />
        <div class="missionText">
          <h3>Mission Statement</h3>
          <p>
            To unify tomorrow's solutions by consistently delivering
            high-quality, versatile, and scalable software solutions.
          </p>
        </div>
      </div>
      <div class="vision">
        <img :src="adsClick" alt="" />
        <div class="visionText">
          <h3>Vision Statement</h3>
          <p>
            To be the leading provider of innovative tech solutions that drive
            societal progress.
          </p>
        </div>
      </div>
    </div>
    <div class="readyToServe">
      <div class="readyToServeHeader">
        <h1>We are ready to serve you!</h1>
        <p>Our comprehensive services help you achieve your goals.</p>
      </div>
      <div class="readyToServeCards">
        <div class="readyToServeCard">
          <div class="readyToServeImg">
            <img :src="readyToServe1" alt="" />
          </div>
          <div class="readyToServeText">
            <h3>Software Development</h3>
            <p>
              We design, develop, and manage robust software solutions that
              scale with your business.
            </p>
          </div>
        </div>
        <div class="readyToServeCard">
          <div class="readyToServeImg">
            <img :src="readyToServe2" alt="" />
          </div>
          <div class="readyToServeText">
            <h3>Digital Skills Training</h3>
            <p>
              We empower your team with the latest digital skills through our
              comprehensive training programs.
            </p>
          </div>
        </div>
        <div class="readyToServeCard">
          <div class="readyToServeImg">
            <img :src="readyToServe3" alt="" />
          </div>
          <div class="readyToServeText">
            <h3>Brand Strategy Formulation</h3>
            <p>
              We craft a powerful brand identity and develop a winning strategy
              for your business long-term success.
            </p>
          </div>
        </div>
        <div class="readyToServeCard">
          <div class="readyToServeImg">
            <img :src="readyToServe4" alt="" />
          </div>
          <div class="readyToServeText">
            <h3>IT & Hardware Support</h3>
            <p>
              Our team provides reliable IT and hardware support to keep your
              business running smoothly.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="whyChooseUs">
      <div class="whyChooseUsHeader">
        <h1>Why choose 3bytz?</h1>
        <p>Expertise, Innovation, and Proven Results</p>
      </div>
      <div class="whyChooseUsBody">
        <div class="whyChooseUsCards1">
          <div class="whyChooseUsCard">
            <div class="whyChooseUsNumber">1</div>
            <div class="whyChooseUsCardBody">
              <div class="whyChooseUsCardBodyTop">
                <h6>Innovation</h6>
                <p>
                  We push boundaries and embrace new technologies to create
                  cutting-edge solutions.
                </p>
              </div>
              <div class="innovation">
                <img :src="innovation" alt="" />
              </div>
            </div>
          </div>
          <div class="whyChooseUsCard">
            <div class="whyChooseUsNumber">2</div>
            <div class="whyChooseUsCardBody">
              <div class="whyChooseUsCardBodyTop">
                <h6>Versatility:</h6>
                <p>
                  We cater to diverse needs, offering a comprehensive range of
                  tech services under one roof.
                </p>
              </div>
              <div class="innovation">
                <img :src="versatility" alt="" />
              </div>
            </div>
          </div>
          <div class="whyChooseUsCard">
            <div class="whyChooseUsNumber">3</div>
            <div class="whyChooseUsCardBody">
              <div class="whyChooseUsCardBodyTop">
                <h6>Excellence:</h6>
                <p>
                  We strive for excellence in everything we do by delivering
                  exceptional results consistently.
                </p>
              </div>
              <div class="innovation">
                <img :src="excellence" alt="" />
              </div>
            </div>
          </div>
        </div>
        <div class="whyChooseUsCards2">
          <div class="whyChooseUsCard">
            <div class="whyChooseUsNumber">4</div>
            <div class="whyChooseUsCardBody">
              <div class="whyChooseUsCardBodyTop">
                <h6>Collaboration:</h6>
                <p>
                  We work closely with our clients to understand their needs and
                  deliver solutions that exceed expectations.
                </p>
              </div>
              <div class="innovation">
                <img :src="collaboration" alt="" />
              </div>
            </div>
          </div>
          <div class="whyChooseUsCard">
            <div class="whyChooseUsNumber">5</div>
            <div class="whyChooseUsCardBody">
              <div class="whyChooseUsCardBodyTop">
                <h6>Integrity:</h6>
                <p>
                  We build trust with our clients through transparency, honesty,
                  and ethical practices.
                </p>
              </div>
              <div class="innovation">
                <img :src="integrity" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="faqQuestionContainer">
      <div class="faqQuestion">
        <h3>Frequently Asked Questions</h3>
        <p>
          If your question is not answered on our FAQ section, feel free to
          contact us and we will ensure to resolve your enquiries.
        </p>
      </div>
      <TheAccordion />
    </div>
    <GetInTouch
      h1="Get in Touch"
      text="Need more information? Reach our to us"
      btnText="Book a Free Consultation"
    />
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
.ourTrusteeContainer {
  padding: 0px 100px 50px 100px;
  gap: 32px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.ourTrustee {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 8px;
}
.companyNumber {
  display: flex;
  justify-content: center;
  padding: 10px 16px;
  background: #fbfcff;
  border: 1px solid #e5e2e1;
  border-radius: 100px;
  gap: 4px;
  align-items: center;
}
.customerStory {
  display: flex;
  align-items: center;
  gap: 4px;
  transition: 0.3s;
  cursor: pointer;
}
.customerStory:hover {
  gap: 8px;
}
.customerStory p {
  color: #005cc9;
  font-weight: 600;
}
.trustedBankLogo {
  max-width: 1030px;
  width: 100%;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
}
.trustedBankLogo img {
  max-width: 158px;
  width: 100%;
}
.aboutUsContainer {
  padding: 50px 100px 50px 100px;
  gap: 16px;
  background: #060320;
  display: flex;
}
.aboutUs {
  display: flex;
  flex-direction: column;
  gap: 16px;
  color: #fff;
}
.aboutUs h1 {
  font-size: 28px;
  font-weight: 700;
  line-height: 36px;
  color: #e0e1f6;
}
.aboutUs p {
  font-size: 18px;
  line-height: 26px;
  color: #e0e1f6;
}
.mission,
.vision {
  display: flex;
  flex-direction: column;
  gap: 24px;
  padding: 20px;
  border-radius: 16px;
  border: 1px solid #f5f3f3;
  background: #fcfcfe;
  gap: 24px;
  width: 100%;
}
.mission img,
.vision img {
  width: fit-content;
}
.missionText,
.visionText {
  display: flex;
  flex-direction: column;
  gap: 4px;
}
.readyToServe {
  display: flex;
  flex-direction: column;
  padding: 50px 100px 50px 100px;
  gap: 32px;
}
.readyToServeHeader {
  display: flex;
  flex-direction: column;
  gap: 8px;
}
.readyToServeHeader h3,
.whyChooseUsHeader h3,
.faqQuestion h3 {
  font-weight: 700;
  font-size: 28px;
  line-height: 36px;
}
.readyToServeHeader p,
.whyChooseUsHeader p,
.faqQuestion p {
  font-size: 18px;
  line-height: 26px;
}
.readyToServeCards {
  display: flex;
  gap: 16px;
  width: 100%;
}
.readyToServeCard {
  padding: 0px 0px 12px 0px;
  display: flex;
  flex-direction: column;
  gap: 24px;
  border-radius: 12px;
  border: 1px solid #eae7e7;
  opacity: 0px;
}
.readyToServeImg {
  padding: 20px;
  display: flex;
  justify-content: center;
}
.readyToServeText {
  padding: 0 12px;
  display: flex;
  flex-direction: column;
  gap: 4px;
}
.readyToServeText h3 {
  font-size: 18px;
  line-height: 26px;
}
.whyChooseUsHeader {
  padding: 50px 100px 0px 100px;
  display: flex;
  flex-direction: column;
  gap: 8px;
}
.whyChooseUsBody {
  padding: 50px 100px 50px 100px;
  display: flex;
  flex-direction: column;
  gap: 24px;
}
.whyChooseUsCards1,
.whyChooseUsCards2 {
  display: flex;
  gap: 16px;
}
.whyChooseUsCard {
  display: flex;
  flex-direction: column;
  padding: 24px;
  gap: 53px;
  border-radius: 16px;
  border: 1px solid #e5e2e1;
  width: 100%;
}
.whyChooseUsNumber {
  padding: 20px 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  border: 2px solid #005cc9;
  color: #005cc9;
  width: fit-content;
  border-radius: 100%;
  font-size: 32px;
  font-weight: 600;
  line-height: 40px;
}
.whyChooseUsCardBody {
  display: flex;
  flex-direction: column;
  gap: 22px;
}
.whyChooseUsCardBodyTop {
  display: flex;
  flex-direction: column;
  gap: 8px;
  font-size: 18px;
}
.whyChooseUsCardBodyTop h6 {
  font-weight: 600;
  font-size: 18px;
}
.innovation img {
  width: 100%;
}
.faqQuestionContainer {
  display: flex;
  padding: 50px 100px 50px 100px;
  justify-content: space-between;
}
.faqQuestion {
  display: flex;
  flex-direction: column;
  gap: 8px;
}

@media screen and (max-width: 640px) {
  .heroSection {
    padding: 50px 24px;
  }
  .techSolution h1 {
    font-size: 32px;
  }
  .ourTrusteeContainer {
    padding: 24px;
  }
  .companyNumber {
    font-size: 12px;
  }
  .trustedBankLogo {
    flex-wrap: wrap;
    gap: 10px;
    justify-content: center;
  }
  .trustedBankLogo img {
    width: 45%;
  }
  .aboutUsContainer {
    flex-direction: column;
    padding: 50px 24px;
  }
  .readyToServeCards,
  .whyChooseUsCards1,
  .whyChooseUsCards2 {
    flex-direction: column;
  }
  .readyToServe {
    padding: 50px 24px;
  }
  .whyChooseUsCard {
    gap: 30px;
  }
  .whyChooseUsCardBodyTop p {
    font-size: 16px;
  }
  .whyChooseUsHeader {
    padding: 50px 24px 0px 24px;
  }
  .whyChooseUsHeader h1 {
    font-size: 18px;
  }
  .whyChooseUsHeader p,
  .aboutUs p {
    font-size: 16px;
  }
  .whyChooseUsBody {
    padding: 50px 24px;
  }
  .whyChooseUsNumber {
    padding: 10px 20px;
  }
  .faqQuestionContainer {
    flex-direction: column;
    padding: 24px;
    gap: 24px;
  }
  .faqQuestion {
    gap: 4px;
  }
  .faqQuestion h3 {
    font-size: 20px;
  }
  .readyToServeHeader h1 {
    font-size: 18px;
  }
  .faqQuestion p,
  .readyToServeHeader p {
    font-size: 16px;
  }
}
/* end */
</style>
