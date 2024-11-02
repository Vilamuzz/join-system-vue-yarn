<script setup lang="ts">
import { defineProps } from 'vue'

defineProps({
  isWhite: {
    type: Boolean,
    default: false,
  },
})
</script>

<template>
  <div
    :class="{ 'icon-white': isWhite }"
    class="flex justify-center space-x-6 mt-4"
  >
    <a
      href="#"
      class="inline-block w-6 h-6 transition-transform duration-300 ease-in-out hover:scale-110"
    >
      <i
        class="block w-full h-full bg-no-repeat bg-center bg-contain"
        style="background-image: url('/src/assets/images/logo/Facebook.svg')"
      ></i>
    </a>

    <a
      href="#"
      class="inline-block w-6 h-6 transition-transform duration-300 ease-in-out hover:scale-110"
    >
      <i
        class="block w-full h-full bg-no-repeat bg-center bg-contain"
        style="background-image: url('/src/assets/images/logo/Twitter.svg')"
      ></i>
    </a>

    <a
      href="https://www.instagram.com/"
      class="inline-block w-6 h-6 transition-transform duration-300 ease-in-out hover:scale-110"
    >
      <i
        class="block w-full h-full bg-no-repeat bg-center bg-contain"
        style="background-image: url('/src/assets/images/logo/Instagram.svg')"
      ></i>
    </a>

    <a
      href="#"
      class="inline-block w-6 h-6 transition-transform duration-300 ease-in-out hover:scale-110"
    >
      <i
        class="block w-full h-full bg-no-repeat bg-center bg-contain"
        style="background-image: url('/src/assets/images/logo/Linkedin.svg')"
      ></i>
    </a>
  </div>
</template>

<style scoped>
.icon-white i {
  filter: invert(1);
}
</style>
