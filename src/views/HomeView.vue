<script setup>
import { ref } from 'vue';


</script>

<template>
  <main class="bg-blue-200 h-screen flex flex-col items-center justify-center">
    <div class="qr-card flex flex-col justify-center items-center bg-white w-11/12 max-w-sm h-fit p-4 rounded-2xl">
      <div class="qr rounded-xl overflow-hidden">
        <img src="../assets/image-qr-code.png" alt="">
      </div>
      <div class="qr-card-title">
        <h1 class="text-[hsl(218,44%,22%)] text-2xl text-center font-bold my-3">
          Improve your front-end <br>
          skills by building projects
        </h1>
      </div>
      <div class="qr-card-msg">
        <p class=" font-normal text-center my-3 text-[hsl(220,15%,55%)]">
          Scan the QR code to visit Frontend <br>
          Mentor and take your coding skills <br>
          to the next level
        </p>
      </div>
    </div>

    <footer class="attribution mt-5">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
      Coded by <a href="https://github.com/GumoDev">GumoDev</a>.
    </footer>
  </main>

</template>

