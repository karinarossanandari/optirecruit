<script setup>
</script>

<template>
  <div class="div">
    <div class="div-2">
      <div class="div-3">OptiRecruit!</div>
      <div class="div-4">
        Aplikasi seleksi dan rekrutmen PT. Human In Partner
      </div>
      <div class="div-5">
        <form class="div-6">
          <div class="div-7">DAFTAR</div>
          <input class="div-8" type="text" placeholder="Masukkan Nama Lengkap" required>
          <input class="div-9" type="email" placeholder="Masukkan Email" required>
          <input class="div-10" type="password" placeholder="Masukkan Password" required>
          <input class="div-11" type="password" placeholder="Konfirmasi Password" required>
        </form>
      </div>
      <button class="div-12" type="submit">Registrasi</button>
    </div>
  </div>
</template>

<style scoped>
.div {
  background-color: #fff;
  display: flex;
  align-items: center;
  font-size: 30px;
  color: #1d2c63;
  font-weight: 700;
  text-align: center;
  justify-content: center;
  padding: 80px 60px;
}
@media (max-width: 991px) {
  .div {
    padding: 0 20px;
  }
}
.div-2 {
  display: flex;
  margin-top: 16px;
  width: 872px;
  max-width: 100%;
  flex-direction: column;
  align-items: center;
}
.div-3 {
  font-family: 'League Spartan', sans-serif;
  font-weight: bold;
  font-size: 130px;
}
@media (max-width: 991px) {
  .div-3 {
    font-family: 'League Spartan', sans-serif;
    font-weight: bold;
    max-width: 100%;
    font-size: 40px;
  }
}
.div-4 {
  font-family: Roboto, sans-serif;
  margin-top: 31px;
}
@media (max-width: 991px) {
  .div-4 {
    max-width: 100%;
  }
}
.div-5 {
  border-radius: 30px;
  background-color: #1d2c63;
  align-self: stretch;
  display: flex;
  margin-top: 40px;
  align-items: center;
  color: #d9d9d9;
  font-weight: 400;
  justify-content: center;
  padding: 53px 60px;
}
@media (max-width: 991px) {
  .div-5 {
    max-width: 100%;
    padding: 0 20px;
  }
}
.div-6 {
  display: flex;
  width: 659px;
  max-width: 100%;
  flex-direction: column;
}
.div-7 {
  color: #fff;
  align-self: center;
  font: 800 48px Roboto, sans-serif;
}
@media (max-width: 991px) {
  .div-7 {
    font-size: 40px;
  }
}
.div-8, .div-9, .div-10, .div-11 {
  font-family: Roboto, sans-serif;
  border-radius: 30px;
  background-color: #fff;
  margin-top: 32px;
  align-items: center;
  justify-content: center;
  padding: 20px 60px;
  border: 1px solid #ccc;
  font-size: 16px;
  color: #333;
  outline: none;
}
.div-8::placeholder, .div-9::placeholder, .div-10::placeholder, .div-11::placeholder {
  color: #aaa;
}
@media (max-width: 991px) {
  .div-8, .div-9, .div-10, .div-11 {
    max-width: 100%;
    padding: 0 20px;
  }
}
.div-12 {
  font-family: Roboto, sans-serif;
  margin-top: 39px;
  padding: 20px 60px;
  border-radius: 30px;
  background-color: #1d2c63;
  color: #fff;
  font-weight: 700;
  cursor: pointer;
  border: none;
}
@media (max-width: 991px) {
  .div-12 {
    max-width: 100%;
    padding: 0 20px;
  }
}
</style>

