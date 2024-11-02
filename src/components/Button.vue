<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import { ref } from 'vue'
import { useRouter } from 'vue-router'

interface Props {
  text?: string
  route?: string
}

const props = withDefaults(defineProps<Props>(), {
  text: 'Button',
  route: '',
})

const buttonText = ref(props.text)
const router = useRouter()

// Fungsi untuk mengarahkan ke halaman yang ditentukan jika ada
const handleClick = () => {
  if (props.route) {
    router.push(props.route)
  }
}
</script>

<template>
  <button
    @click="handleClick"
    class="py-4 px-12 bg-blue-600 text-white text-lg font-bold hover:bg-yellow-300 transition duration-300"
  >
    {{ buttonText }}
  </button>
</template>
