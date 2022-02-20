<script setup lang="ts">
import qrCodeImg from "@/assets/images/image-qr-code.png";
</script>

<template>
  <div class="qr-code-container">
    <img
      :src="qrCodeImg"
      alt="QR Code to visit frontend mentors"
      class="qr-code-img"
    />
    <div class="qr-code-text">
      <h1>Improve your front-end skills by building projects</h1>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </div>
</template>

<style scoped>
.qr-code-img {
  border-radius: 0.5rem;
  width: 100%;
}

.qr-code-container {
  text-align: center;
  background: white;
  padding: 0.75rem;
  border-radius: 1rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 300px;
  box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1),
    0 8px 10px -6px rgb(0 0 0 / 0.1);
}

@media screen and (min-width: 768px) {
  .qr-code-container {
    max-width: 250px;
  }
}

.qr-code-text {
  padding: 1rem;
}
</style>
