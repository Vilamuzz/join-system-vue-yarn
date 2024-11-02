<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import { defineProps, withDefaults } from 'vue'

// Mendefinisikan properti komponen
interface Props {
  text?: string
  subtext?: string
  showText?: boolean
  breadcrumb?: string
}

// Mengatur nilai default pada props
const props = withDefaults(defineProps<Props>(), {
  text: 'Title',
  subtext: 'SubTitle',
  showText: false,
  breadcrumb: 'Breadcrumb',
})
</script>

<template>
  <div class="w-full flex flex-col bg-purple-50">
    <div
      class="text-slate-800 mx-96 text-center flex justify-center flex-grow flex-col gap-y-1 items-center py-20"
    >
      <div class="tracking-[-2px] leading-[64px] font-bold text-5xl">
        {{ props.text }}
      </div>
      <div class="tracking-[0px] leading-7 mb-4">
        {{ props.subtext }}
      </div>

      <!-- Menampilkan teks blog hanya jika showText bernilai true -->
      <div
        v-if="props.showText"
        class="tracking-[3px] text-slate-800 uppercase font-medium leading-5"
      >
        {{ props.breadcrumb }}
      </div>
    </div>
  </div>
</template>
