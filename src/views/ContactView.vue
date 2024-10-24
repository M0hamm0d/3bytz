<script setup></script>
<template>
  <div class="container">
    <div class="header">
      <h1>Get in Touch with Us</h1>
      <p>
        We're here to help and answer any questions you might have. We look
        forward to hearing from you!
      </p>
    </div>
    <div class="location-container">
      <div class="location">
        <div class="location-img">
          <img src="../assets/images/location-logo.png" alt="" />
        </div>
        <div class="location-address">
          <div class="names">
            <div class="">
              <h3>First Name</h3>
              <input type="text" placeholder="Input your first name" />
            </div>
            <div class="">
              <h3>Last Name</h3>
              <input type="text" placeholder="Input your Last name" />
            </div>
          </div>
          <div class="email">
            <h3>Email</h3>
            <input type="text" placeholder="Input your email address" />
          </div>
          <div class="phone-no">
            <h3>Phone Number</h3>
            <input type="text" placeholder="Input your mobile number" />
          </div>
          <div class="message">
            <h3>Message</h3>
            <div class="input">
              <input type="text" placeholder="Type your message" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  flex-direction: column;
  padding: 50px 100px 50px 100px;
  gap: 52px;
}
.header {
  display: flex;
  flex-direction: column;
  gap: 8px;
}
.header h1 {
  text-align: center;
  font-size: 40px;
  font-weight: 600;
  line-height: 48px;
}
.header p {
  width: 644px;
  text-align: center;
  margin: 0 auto;
  font-size: 18px;
}
.location-container {
  display: flex;
  flex-direction: column;
  gap: 35px;
}
.location {
  display: flex;
  gap: 35px;
}
.location-img {
  position: relative;
  width: 100%;
  flex: 1;
}
.location-img img {
  width: 100%;
}
.location-address {
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 32px;
}
.names {
  display: flex;
  gap: 16px;
}
.names > div {
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 12px;
}
.message {
  display: flex;
  flex-direction: column;
  gap: 12px;
  height: 100%;
}
.location-address .message .input {
  display: flex;
  flex: 1;
  align-items: flex-start;
  height: 100%;
}
.email,
.phone-no {
  display: flex;
  flex-direction: column;
  gap: 12px;
}
.location-address h3 {
  font-size: 16px;
}
.location-address input {
  min-height: 40px;
  padding: 10px 12px 10px 12px;
  gap: 10px;
  border-radius: 8px;
  border: 1px solid #e5e2e1;
}
</style>
