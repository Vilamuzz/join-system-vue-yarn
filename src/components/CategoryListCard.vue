<script setup lang="ts">
import { defineProps } from 'vue'

defineProps({
  title: {
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
  <div
    class="border border-gray-300 p-5 text-left hover:bg-blue-500 hover:text-white transition duration-300 flex flex-row items-center w-[100%] gap-x-4"
  >
    <img
      :src="imageSrc"
      alt=""
      class="w-10 h-auto bg-gray-100 border rounded-lg"
    />
    <h2 class="text-2xl font-semibold">{{ title }}</h2>
  </div>
</template>
