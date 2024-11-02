<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
</script>
<template>
  <MainLayout>
    <div
      class="font-inter text-center w-full flex flex-col gap-y-3 items-center mt-32 mb-24 mx-auto"
      style="max-width: 768px"
    >
      <div class="tracking-[3px] text-slate-800 uppercase font-black leading-5">
        Contact us
      </div>
      <div class="flex justify-center pr-px self-stretch items-center">
        <div
          class="tracking-[-2px] leading-[64px] text-slate-800 font-sen text-center font-bold text-5xl"
        >
          Let’s Start a Conversation
        </div>
      </div>
      <div
        class="text-zinc-500 tracking-[0px] self-stretch pt-3 items-center justify-center flex leading-7"
      >
        <p class="text-center">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim.
        </p>
      </div>
    </div>
    <div class="w-full flex flex-col">
      <div
        class="tracking-[0px] text-neutral-600 pr-[74px] flex justify-center pl-16 flex-grow flex-col gap-y-4 bg-yellow-300 py-12 mx-auto max-w-[768px]"
      >
        <div
          class="min-[758px]:flex-nowrap font-inter gap-y-[18px] leading-5 text-sm flex flex-wrap justify-center gap-x-11 items-center"
        >
          <div
            class="gap-y-[15px] flex-shrink-0 flex w-72 flex-col items-start"
          >
            <div>Working hours</div>
            <Line class="flex-shrink-0 h-px self-stretch" />
          </div>
          <div
            class="gap-y-[15px] flex-shrink-0 flex w-72 flex-col items-start"
          >
            <div>Contact Us</div>
            <Line1 class="flex-shrink-0 h-px self-stretch" />
          </div>
        </div>
        <div
          class="min-[758px]:flex-nowrap gap-x-[71px] gap-y-[30px] flex flex-wrap items-start"
        >
          <div>
            <div class="font-sen font-bold leading-8 text-xl w-56">
              Monday To Friday
            </div>
            <div class="font-sen font-bold leading-8 text-xl w-60">
              9:00 AM to 8:00 PM
            </div>
            <div class="font-inter leading-7">
              Our Support Team is available 24/7
            </div>
          </div>
          <div class="flex-shrink-0 w-48">
            <div class="font-sen font-bold leading-8 text-xl self-stretch">
              020 7993 2905
            </div>
            <div class="font-inter leading-7">hello@finsweet.com</div>
          </div>
        </div>
      </div>
    </div>
    <div class="w-full flex flex-col items-center mb-32 mt-14">
      <div
        class="min-w-[758px] p-6 border-zinc-500/50 flex flex-grow items-center border border-solid rounded-sm mb-4"
      >
        <input
          type="text"
          placeholder="Full Name"
          class="w-full bg-transparent text-slate-800 leading-7 border-none outline-none placeholder:text-slate-400"
        />
      </div>
      <div
        class="min-w-[758px] border-zinc-500/50 flex p-6 flex-grow items-center border border-solid rounded-sm mb-4"
      >
        <input
          type="email"
          placeholder="Email"
          class="w-full bg-transparent text-slate-800 font-inter leading-7 border-none outline-none placeholder:text-slate-400"
        />
      </div>
      <div class="min-w-[758px] flex mb-4 gap-4">
        <div
          class="w-1/2 border-zinc-500/50 flex p-6 flex-grow items-center border border-solid rounded-sm"
        >
          <select
            class="w-full bg-transparent text-slate-800 font-inter leading-7 border-none outline-none"
          >
            <option value="" disabled selected>Province</option>
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
          </select>
        </div>
        <div
          class="w-1/2 border-zinc-500/50 flex p-6 flex-grow items-center border border-solid rounded-sm"
        >
          <select
            class="w-full bg-transparent text-slate-800 font-inter leading-7 border-none outline-none"
          >
            <option value="" disabled selected>City</option>
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
          </select>
        </div>
      </div>
      <div
        class="min-w-[758px] border-zinc-500/50 flex p-6 flex-grow items-center border border-solid rounded-sm mb-4"
      >
        <input
          type="text"
          placeholder="Message"
          class="w-full bg-transparent text-slate-800 font-inter leading-7 border-none outline-none placeholder:text-slate-400 h-24"
        />
      </div>
      <div class="flex flex-col">
        <button
          class="py-4 px-80 bg-blue-600 text-blue-950 text-lg font-bold hover:bg-yellow-300 hover:text-white transition duration-300"
        >
          Send Message
        </button>
      </div>
    </div>
  </MainLayout>
</template>
