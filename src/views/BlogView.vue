<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import Button from '@/components/Button.vue'
import Join from '@/components/Join.vue'
import CategoryCard from '@/components/CategoryCard.vue'
</script>
<template>
  <MainLayout>
    <div class="w-full flex flex-col">
      <div
        class="pr-[736px] bg-purple-50 flex relative justify-center pl-20 flex-col gap-y-4 py-24"
      >
        <img
          class="w-[515px] absolute right-20 inset-y-20"
          src="../assets/images/man-in-white-dress-shirt-sitting-on-black-rolling-chair-while-facing-black-computer-set-and-smiling-840996.png"
          loading="lazy"
        />
        <div
          class="tracking-[3px] text-slate-800 uppercase font-medium leading-5"
        >
          Featured Post
        </div>
        <div class="[max-width:624px] pt-1 self-stretch">
          <div
            class="tracking-[-2px] leading-[48px] text-slate-800 font-sen font-bold text-4xl items-center flex"
          >
            <p>Step-by-step guide to choosing great font pairs</p>
          </div>
        </div>
        <div class="font-medium leading-5 text-sm">
          <span>
            <span class="text-neutral-600">By </span>
            <span class="text-yellow-300">John Doe </span>
            <span class="text-neutral-600">l May 23, 2022</span>
          </span>
        </div>
        <div class="text-zinc-500 leading-7 items-start flex self-stretch">
          <p>
            Duis aute irure dolor in reprehenderit in voluptate velit esse
            cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
            cupidatat non proident.
          </p>
        </div>
        <div class="flex pt-4 items-end px-1">
          <Button text="Read More &gt" route="/blog/post" />
        </div>
      </div>
    </div>
    <div class="max-w-[1440px] mx-16 py-16">
      <h2 class="text-3xl font-semibold mb-8">All Post</h2>
      <div class="bg-gray-300 h-[1px] mb-14"></div>
      <div
        class="flex flex-wrap justify-start flex-grow gap-x-8 gap-y-8 items-center mb-8"
      >
        <img
          class="w-[390px] h-auto"
          src="../assets/images/two-women-in-front-of-dry-erase-board-1181533.png"
          loading="lazy"
        />
        <div class="w-[624px] flex flex-col gap-y-4">
          <div
            class="tracking-[3px] font-inter uppercase font-semibold leading-5 text-yellow-300 w-44"
          >
            Startup
          </div>
          <div class="[max-width:624px] flex pt-1 pr-5 items-end">
            <div
              class="tracking-[-2px] leading-[48px] text-slate-800 font-sen font-bold text-4xl items-end flex flex-grow"
            >
              <p>Design tips for designers that cover everything you need</p>
            </div>
          </div>
          <div
            class="tracking-[0px] text-zinc-500 font-inter leading-7 items-start flex"
          >
            <p>
              Duis aute irure dolor in reprehenderit in voluptate velit esse
              cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
              cupidatat non proident.
            </p>
          </div>
        </div>
      </div>
      <div
        class="flex flex-wrap justify-start flex-grow gap-x-8 gap-y-8 items-center mb-8"
      >
        <img
          class="w-[390px] h-auto"
          src="../assets/images/two-women-in-front-of-dry-erase-board-1181533.png"
          loading="lazy"
        />
        <div class="w-[624px] flex flex-col gap-y-4">
          <div
            class="tracking-[3px] font-inter uppercase font-semibold leading-5 text-yellow-300 w-44"
          >
            Startup
          </div>
          <div class="[max-width:624px] flex pt-1 pr-5 items-end">
            <div
              class="tracking-[-2px] leading-[48px] text-slate-800 font-sen font-bold text-4xl items-end flex flex-grow"
            >
              <p>Design tips for designers that cover everything you need</p>
            </div>
          </div>
          <div
            class="tracking-[0px] text-zinc-500 font-inter leading-7 items-start flex"
          >
            <p>
              Duis aute irure dolor in reprehenderit in voluptate velit esse
              cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
              cupidatat non proident.
            </p>
          </div>
        </div>
      </div>
      <div
        class="flex flex-wrap justify-start flex-grow gap-x-8 gap-y-8 items-center mb-8"
      >
        <img
          class="w-[390px] h-auto"
          src="../assets/images/two-women-in-front-of-dry-erase-board-1181533.png"
          loading="lazy"
        />
        <div class="w-[624px] flex flex-col gap-y-4">
          <div
            class="tracking-[3px] font-inter uppercase font-semibold leading-5 text-yellow-300 w-44"
          >
            Startup
          </div>
          <div class="[max-width:624px] flex pt-1 pr-5 items-end">
            <div
              class="tracking-[-2px] leading-[48px] text-slate-800 font-sen font-bold text-4xl items-end flex flex-grow"
            >
              <p>Design tips for designers that cover everything you need</p>
            </div>
          </div>
          <div
            class="tracking-[0px] text-zinc-500 font-inter leading-7 items-start flex"
          >
            <p>
              Duis aute irure dolor in reprehenderit in voluptate velit esse
              cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
              cupidatat non proident.
            </p>
          </div>
        </div>
      </div>
      <div
        class="flex flex-wrap justify-start flex-grow gap-x-8 gap-y-8 items-center mb-8"
      >
        <img
          class="w-[390px] h-auto"
          src="../assets/images/two-women-in-front-of-dry-erase-board-1181533.png"
          loading="lazy"
        />
        <div class="w-[624px] flex flex-col gap-y-4">
          <div
            class="tracking-[3px] font-inter uppercase font-semibold leading-5 text-yellow-300 w-44"
          >
            Startup
          </div>
          <div class="[max-width:624px] flex pt-1 pr-5 items-end">
            <div
              class="tracking-[-2px] leading-[48px] text-slate-800 font-sen font-bold text-4xl items-end flex flex-grow"
            >
              <p>Design tips for designers that cover everything you need</p>
            </div>
          </div>
          <div
            class="tracking-[0px] text-zinc-500 font-inter leading-7 items-start flex"
          >
            <p>
              Duis aute irure dolor in reprehenderit in voluptate velit esse
              cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
              cupidatat non proident.
            </p>
          </div>
        </div>
      </div>
      <div
        class="flex flex-wrap justify-start flex-grow gap-x-8 gap-y-8 items-center mb-8"
      >
        <img
          class="w-[390px] h-auto"
          src="../assets/images/two-women-in-front-of-dry-erase-board-1181533.png"
          loading="lazy"
        />
        <div class="w-[624px] flex flex-col gap-y-4">
          <div
            class="tracking-[3px] font-inter uppercase font-semibold leading-5 text-yellow-300 w-44"
          >
            Startup
          </div>
          <div class="[max-width:624px] flex pt-1 pr-5 items-end">
            <div
              class="tracking-[-2px] leading-[48px] text-slate-800 font-sen font-bold text-4xl items-end flex flex-grow"
            >
              <p>Design tips for designers that cover everything you need</p>
            </div>
          </div>
          <div
            class="tracking-[0px] text-zinc-500 font-inter leading-7 items-start flex"
          >
            <p>
              Duis aute irure dolor in reprehenderit in voluptate velit esse
              cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
              cupidatat non proident.
            </p>
          </div>
        </div>
      </div>
      <div class="flex justify-center space-x-4">
        <a
          href="#"
          class="text-gray-500 hover:text-black transition duration-300 transform hover:scale-105"
          >Prev</a
        >
        <a
          href="#"
          class="text-gray-500 hover:text-black transition duration-300 transform hover:scale-105"
          >Next</a
        >
      </div>
    </div>

    <div class="max-w-[1440px] mx-16 py-16">
      <h2 class="text-3xl font-semibold mb-8">All Categories</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
        <CategoryCard
          title="Business"
          imageSrc="src/assets/images/icon/Icon.png"
          description="Deskripsi singkat untuk kategori 1."
        />
        <CategoryCard
          title="Startup"
          imageSrc="src/assets/images/icon/Icon2.png"
          description="Deskripsi singkat untuk kategori 2."
        />
        <CategoryCard
          title="Economy"
          imageSrc="src/assets/images/icon/Icon3.png"
          description="Deskripsi singkat untuk kategori 3."
        />
        <CategoryCard
          title="Technology"
          imageSrc="src/assets/images/icon/Icon4.png"
          description="Deskripsi singkat untuk kategori 4."
        />
      </div>
      <Join />
    </div>
  </MainLayout>
</template>
