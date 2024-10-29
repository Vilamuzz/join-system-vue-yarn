<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import { ref } from 'vue'

interface Props {
  text?: string
}
const props = withDefaults(defineProps<Props>(), {
  text: 'Button',
})
const buttonText = ref(props.text)
</script>

<template>
  <button
    class="py-4 px-12 bg-blue-600 text-white text-lg font-bold hover:bg-yellow-500 transition duration-300"
  >
    {{ buttonText }}
  </button>
</template>
