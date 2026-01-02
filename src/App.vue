<template>
  <div class="bg relative overflow-hidden max-w-">
    <div class="relative mx-auto max-w-7xl">
      <img src="./assets/norm_bird.png" class="top-72 slide-bird pl-10 absolute" alt="">
      <img src="./assets/norm_bird.png" class="top-80 pl-46 absolute" alt="">
      <img src="./assets/norm_bird.png" class="top-96 pl-240 absolute" alt="">
      <img src="./assets/norm_bird.png" class="top-96 pl-[85%] absolute" alt="">
    </div>
    <Hero />

    <div class="flying-birds">
      <img src="./assets/bird4.png" class="bird bird-right" />
      <img src="./assets/bird2.png" class="bird bird-left" />
    </div>

    <div class="relative">
      <!-- Clouds -->
      <img src="./assets/clouds.png" alt="" class="block w-full">

      <!-- Birds layer -->
      <div class="absolute inset-0 z-10 flex gap-28 items-start">
        <img src="./assets/bird4.png" class="shrink-0 mt-36 max-w-none w-auto h-auto">
        <img src="./assets/bird3.png" class="shrink-0 ml-32 pt-32 max-w-none w-fit h-auto">
        <img src="./assets/bird2.png" class="shrink-0 mt-32 pl-90 max-w-none w-auto h-auto">
        <img src="./assets/bird1.png" class="shrink-0 mt-16 max-w-none w-auto h-auto">
      </div>
    </div>
  </div>

</template>

<script setup>
import { ref } from 'vue'
import Hero from './components/Hero.vue'

</script>

<style scoped>
.bg {
  background-image: url(./assets/Hero_bg.png);

}

@keyframes slideUp {
  from {
    transform: translateY(300px);
    opacity: 0;
  }

  to {
    transform: translateY(0);
    opacity: 1;
  }
}

.slide-bird {
  animation: slideUp 0.6s ease-out forwards;
}

.bird {
  position: absolute;
  width: 120px;
  will-change: transform;
  z-index: 1;
  animation-delay: 10s;
}

.bird-right {
  left: -120px;
  animation: fly-right 5s cubic-bezier(.4, 0, .2, 1) forwards;
}


.bird-left {
  right: -120px;
  transform: scaleX(-1);
  animation: fly-left 5s cubic-bezier(.4, 0, .2, 1) forwards;
}

@keyframes fly-right {
  from {
    transform: translate(0, 0);
  }

  to {
    transform: translate(120vw, -120vh);
  }
}

@keyframes fly-left {
  from {
    transform: translate(0, 0);
  }

  to {
    transform: translate(-120vw, -120vh);
  }
}
</style>
