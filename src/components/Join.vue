<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import Button from '../components/Button.vue'
</script>
<template>
  <div class="text-center max-w-[1440px] flex flex-col gap-y-4 m-24">
    <div
      class="tracking-[-2px] leading-[48px] text-slate-800 font-sen font-bold text-4xl items-center flex justify-center"
    >
      <p class="text-center">Join our team to be a part<br />of our story</p>
    </div>
    <div
      class="pl-[5px] text-zinc-500 tracking-[0px] font-inter pr-1 items-center justify-center flex leading-7"
    >
      <p class="text-center">
        Lorem ipsum dolor sit amet, consectetur adipiscing<br />
        elit, sed do eiusmod tempor incididunt.
      </p>
    </div>
    <div class="flex justify-center pt-4 items-end">
      <Button text="Join Now" />
    </div>
  </div>
</template>
