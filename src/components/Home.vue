<script setup>
import { useRouter } from 'vue-router'

const router = useRouter()

const goToFormPage = () => {
  router.push({ name: 'FormPage' })
}
</script>

<template>
  <div class="main-content">
    <img loading="lazy" srcSet="src/assets/gambar1.png" class="background-img" />
    <div class="text-container">
      <div class="title">OptiRecruit!</div>
      <div class="subtitle">
        Aplikasi seleksi dan rekrutmen PT. Human In Partner
      </div>
      <button class="cta" @click="goToFormPage">GABUNG BERSAMA KAMI</button>
    </div>
  </div>
</template>

<style scoped>
.main-content {
  background-color: #1D2C63;
  display: flex;
  flex-direction: column;
  overflow: hidden;
  position: relative;
  min-height: 100vh; /* Make sure it takes full viewport height */
  width: 100%;
  align-items: center;
  justify-content: center;
  padding: 80px 60px;
}

@media (max-width: 991px) {
  .main-content {
    max-width: 100%;
    padding: 0 20px;
  }
}

.background-img {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
  opacity: 0.61; /* 61% to make it 39% transparent */
}

.text-container {
  position: relative;
  display: flex;
  width: 711px;
  max-width: 100%;
  flex-direction: column;
  margin: 200px 0 100px;
}

@media (max-width: 991px) {
  .text-container {
    margin: 40px 0;
  }
}

.title {
  font: 130px League Spartan, sans-serif;
  color: white;
}

@media (max-width: 991px) {
  .title {
    max-width: 100%;
    font-size: 40px;
  }
}

.subtitle {
  color: white;
  margin-top: 18px;
  font: 30px Roboto, sans-serif;
}

@media (max-width: 991px) {
  .subtitle {
    max-width: 100%;
  }
}

.cta {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  border-radius: 60px;
  background-color: #d9d9d9; /* Replace with var(--cta-bg-color) if you have this variable defined */
  color: #1d2c63; /* Replace with var(--cta-text-color) if you have this variable defined */
  margin: 32px 33px 0;
  padding: 20px 60px;
  font: 32px Roboto, sans-serif;
  font-weight: bolder;
  cursor: pointer;
  border: none;
  outline: none;
  transition: background-color 0.3s ease;
}

.cta:hover {
  background-color: #bfbfbf; /* Slightly darker shade for hover effect */
}

@media (max-width: 991px) {
  .cta {
    max-width: 100%;
    margin-right: 10px;
    padding: 10px 20px;
  }
}
</style>
