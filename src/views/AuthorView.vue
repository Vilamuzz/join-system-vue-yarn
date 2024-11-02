<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import SocialMedia from '@/components/SocialMedia.vue'
</script>
<template>
  <MainLayout>
    <div class="bg-gray-200 px-44 pt-24 flex flex-col items-center">
      <!-- Container Gambar dan Informasi -->
      <div class="flex flex-row w-full">
        <!-- Gambar -->
        <div class="w-[80%]">
          <img
            src="@/assets/images/close-up-photography-of-man-wearing-sunglasses.png"
            alt=""
            loading="lazy"
            class="w-[250px]"
          />
        </div>

        <!-- Informasi -->
        <div class="px-10 flex flex-col">
          <h1 class="font-bold text-4xl mb-8">
            Hey there, I’m Andrew Johnson and welcome to my Blog
          </h1>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Non
            blandit massa enim nec. Scelerisque viverra mauris in aliquam sem.
            At risus viverra adipiscing at in tellus.
          </p>
          <div class="relative">
            <div class="absolute -left-4">
              <SocialMedia class="scale-75" />
            </div>
          </div>
        </div>
      </div>

      <!-- Div Kuning di Bawah Gambar dan Informasi -->
      <div class="w-full h-5 bg-yellow-300 mt-20"></div>
    </div>
    <div class="mx-44 my-32">
      <div class="flex flex-col">
        <h1 class="font-bold text-4xl">My Posts</h1>
        <div class="flex flex-col gap-y-4 my-10">
          <div class="flex flex-row w-full">
            <div class="w-[320px]">
              <img
                src="@/assets/images/stained-glass-high-rise-building-1106476.png"
                loading="lazy"
                alt=""
                class="w-[320px] h-auto"
              />
            </div>
            <div class="w-1/2 px-10 flex flex-col gap-y-4">
              <h2
                class="tracking-[3px] uppercase font-semibold leading-5 text-yellow-300 w-44"
              >
                Business
              </h2>
              <h3 class="text-3xl font-bold">
                Font sizes in UI design: The complete guide to follow
              </h3>
              <p class="text-gray-500">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>
          </div>
        </div>
        <div class="flex flex-col gap-y-4 my-10">
          <div class="flex flex-row w-full">
            <div class="w-[320px]">
              <img
                src="@/assets/images/man-in-black-crew-neck-t-shirt-sitting-beside-woman-in-gray-crew-neck-t-shirt-3153201.png"
                loading="lazy"
                alt=""
                class="w-[320px] h-auto"
              />
            </div>
            <div class="w-1/2 px-10 flex flex-col gap-y-4">
              <h2
                class="tracking-[3px] uppercase font-semibold leading-5 text-yellow-300 w-44"
              >
                Economy
              </h2>
              <h3 class="text-3xl font-bold">
                How to build rapport with your web design clients
              </h3>
              <p class="text-gray-500">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </MainLayout>
</template>
