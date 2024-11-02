<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import { defineProps } from 'vue'

defineProps({
  title: {
    type: String,
    required: true,
  },
  description: {
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
  <router-link
    to="/category"
    class="border border-gray-300 p-7 text-left hover:bg-blue-500 hover:text-white transition duration-300"
  >
    <img
      :src="imageSrc"
      alt=""
      class="w-10 h-auto mb-2 bg-gray-100 border rounded-lg"
    />
    <slot></slot>
    <h3 class="text-2xl font-semibold mb-1">{{ title }}</h3>
    <p class="text-sm">{{ description }}</p>
  </router-link>
</template>
