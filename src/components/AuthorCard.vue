<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import { defineProps } from 'vue'
import { RouterLink } from 'vue-router'
import SocialMedia from './SocialMedia.vue'

defineProps({
  name: {
    type: String,
    required: true,
  },
  position: {
    type: String,
    required: true,
  },
  imageSrc: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <RouterLink
    to="/author"
    class="block hover:shadow-lg transition-shadow duration-300 ease-in-out"
  >
    <div
      class="flex flex-col items-center bg-gray-200 p-6 cursor-pointer hover:bg-gray-300 transition duration-300 ease-in-out"
    >
      <img :src="imageSrc" alt="Author" class="w-24 h-24 rounded-full mb-4" />
      <h3 class="text-lg font-semibold">{{ name }}</h3>
      <p class="text-sm text-gray-600">{{ position }}</p>
      <div class="flex space-x-2 mt-2">
        <SocialMedia class="scale-75" />
      </div>
    </div>
  </RouterLink>
</template>
