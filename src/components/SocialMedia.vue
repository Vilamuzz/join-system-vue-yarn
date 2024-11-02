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
      <img
        src="@/assets/images/logo/Facebook.svg"
        alt=""
        loading="lazy"
        class="block w-full h-full bg-no-repeat bg-center bg-contain"
      />
    </a>

    <a
      href="#"
      class="inline-block w-6 h-6 transition-transform duration-300 ease-in-out hover:scale-110"
    >
      <img
        src="@/assets/images/logo/Twitter.svg"
        alt=""
        loading="lazy"
        class="block w-full h-full bg-no-repeat bg-center bg-contain"
      />
    </a>

    <a
      href="https://www.instagram.com/"
      class="inline-block w-6 h-6 transition-transform duration-300 ease-in-out hover:scale-110"
    >
      <img
        src="@/assets/images/logo/Instagram.svg"
        alt=""
        loading="lazy"
        class="block w-full h-full bg-no-repeat bg-center bg-contain"
      />
    </a>

    <a
      href="#"
      class="inline-block w-6 h-6 transition-transform duration-300 ease-in-out hover:scale-110"
    >
      <img
        src="@/assets/images/logo/Linkedin.svg"
        alt=""
        loading="lazy"
        class="block w-full h-full bg-no-repeat bg-center bg-contain"
      />
    </a>
  </div>
</template>

<style scoped>
.icon-white {
  filter: invert(100%) sepia(100%) saturate(0%) hue-rotate(180deg)
    brightness(200%) contrast(100%);
}
</style>
