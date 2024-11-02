<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
defineProps<{ title: string }>()
</script>
<template>
  <div
    class="border-2 border-zinc-400 rounded-full py-3 px-4 flex-grow text-center hover:bg-zinc-400 hover:text-white transition-colors duration-300"
  >
    {{ title }}
  </div>
</template>
