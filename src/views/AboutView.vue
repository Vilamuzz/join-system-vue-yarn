<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import Join from '@/components/Join.vue'
import AuthorCard from '@/components/AuthorCard.vue'
</script>
<template>
  <MainLayout>
    <div class="mx-16">
      <div class="relative mt-96">
        <img
          src="@/assets/images/photo-of-woman-wearing-eyeglasses-3184405.png"
          alt=""
        />
        <div
          class="flex flex-row ml-10 items-center mt-20 absolute -top-[380px] left-20"
        >
          <div class="w-[800px] text-slate-800 p-16 bg-white">
            <h1 class="tracking-[3px] uppercase font-medium leading-5 mb-4">
              About Us
            </h1>
            <h2
              class="tracking-[-2px] leading-[64px] font-sen font-bold text-5xl items-start flex self-stretch"
            >
              We are a team of content writers who share their learnings
            </h2>
          </div>
          <div class="w-[60%] p-5">
            <p class="tracking-[0px] text-neutral-600 leading-7">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>
        </div>
        <div class="absolute bottom-0 w-2/3">
          <div
            class="bg-blue-600 flex flex-row ml-24 text-white items-center gap-x-8 p-8 w-[70%]"
          >
            <div>
              <h1 class="font-bold text-4xl">12+</h1>
              <p>Blogs Published</p>
            </div>
            <div>
              <h1 class="font-bold text-4xl">18K+</h1>
              <p>Views on Finsweet</p>
            </div>
            <div>
              <h1 class="font-bold text-4xl">30K+</h1>
              <p>Total Active Users</p>
            </div>
          </div>
          <div class="w-full bg-yellow-300 h-5 ml-24"></div>
        </div>
      </div>
      <div class="bg-gray-100 flex flex-row gap-x-8 pt-32 px-20 pb-16">
        <div class="flex flex-col gap-y-4">
          <h1 class="font-semibold leading-none tracking-[3px]">OUR MISSION</h1>
          <h2 class="text-3xl font-bold tracking-tighter leading-10">
            Creating valuable content for creatives all around the world
          </h2>
          <p class="text-gray-500">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Non
            blandit massa enim nec. Scelerisque viverra mauris in aliquam sem.
            At risus viverra adipiscing at in tellus.
          </p>
        </div>
        <div class="flex flex-col gap-y-4">
          <h1 class="font-semibold leading-none tracking-[3px]">OUR VISION</h1>
          <h2 class="text-3xl font-bold tracking-tighter leading-10">
            A platform that empowers individuals to improve
          </h2>
          <p class="text-gray-500">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Non
            blandit massa enim nec. Scelerisque viverra mauris in aliquam sem.
            At risus viverra adipiscing at in tellus.
          </p>
        </div>
      </div>
      <div class="flex flex-row my-20 items-center gap-x-8">
        <div class="w-1/2 flex flex-col gap-y-4 pr-24">
          <h1 class="font-bold leading-none text-3xl">Our team of creatives</h1>
          <h2 class="text-xl font-semibold">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt.
          </h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat.
          </p>
        </div>
        <div class="w-1/2 relative">
          <img
            src="@/assets/images/ground-group-growth-hands-461049.png"
            loading="lazy"
            alt=""
          />
          <div
            class="absolute top-32 -left-10 w-20 h-20 bg-blue-600 rounded-tl-[30px]"
          ></div>
        </div>
      </div>
      <div class="flex flex-row my-20 items-center gap-x-8">
        <div class="w-1/2 relative">
          <img
            src="@/assets/images/three-persons-sitting-on-the-stairs-talking-with-each-other-1438072.png"
            loading="lazy"
            alt=""
          />
          <div
            class="absolute -bottom-10 left-20 w-20 h-20 bg-yellow-300 rounded-full"
          ></div>
        </div>
        <div class="w-1/2 flex flex-col gap-y-4 pr-24">
          <h1 class="font-bold leading-none text-3xl">Our team of creatives</h1>
          <h2 class="text-xl font-semibold">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt.
          </h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat.
          </p>
        </div>
      </div>
      <div class="my-32">
        <h1 class="text-3xl font-bold mb-8 text-center">List of Authors</h1>
        <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
          <AuthorCard
            name="Author Name 1"
            position="Position 1"
            imageSrc="src/assets/images/man-in-yellow-button-up-shirt-wearing-black-framed-eyeglasses-7562313.png"
          />

          <AuthorCard
            name="Author Name 2"
            position="Position 2"
            imageSrc="src/assets/images/woman-in-white-and-black-striped-shirt-wearing-black-sunglasses-3671083.png"
          />

          <AuthorCard
            name="Author Name 3"
            position="Position 3"
            imageSrc="src/assets/images/fashion-woman-cute-shoes-5704849.png"
          />

          <AuthorCard
            name="Author Name 4"
            position="Position 4"
            imageSrc="src/assets/images/content-baker-with-delicious-puff-in-cafeteria-6205509.png"
          />
          <AuthorCard
            name="Author Name 1"
            position="Position 1"
            imageSrc="src/assets/images/man-in-yellow-button-up-shirt-wearing-black-framed-eyeglasses-7562313.png"
          />

          <AuthorCard
            name="Author Name 2"
            position="Position 2"
            imageSrc="src/assets/images/woman-in-white-and-black-striped-shirt-wearing-black-sunglasses-3671083.png"
          />

          <AuthorCard
            name="Author Name 3"
            position="Position 3"
            imageSrc="src/assets/images/fashion-woman-cute-shoes-5704849.png"
          />

          <AuthorCard
            name="Author Name 4"
            position="Position 4"
            imageSrc="src/assets/images/content-baker-with-delicious-puff-in-cafeteria-6205509.png"
          />
        </div>
      </div>
    </div>
    <Join />
  </MainLayout>
</template>
