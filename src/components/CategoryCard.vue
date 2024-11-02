<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import { defineProps } from 'vue'

defineProps({
  title: {
    type: String,
    required: false,
  },
  description: {
    type: String,
    required: false,
  },
})
</script>
<template>
  <router-link
    to="/category"
    class="border border-gray-300 p-7 text-left hover:bg-blue-500 hover:text-white transition duration-300"
  >
    <slot></slot>
    <h3 class="text-2xl font-semibold mb-1">{{ title }}</h3>
    <p class="text-sm">{{ description }}</p>
  </router-link>
</template>
