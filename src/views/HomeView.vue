<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import Button from '@/components/Button.vue'
import Join from '@/components/Join.vue'
import AuthorCard from '@/components/AuthorCard.vue'
import CategoryCard from '@/components/CategoryCard.vue'
import PostCard from '@/components/PostCard.vue'
import backgroundImage from '@/assets/images/man-in-black-suit-wearing-eye-glasses-sitting-on-gray-sofa-using-macbook-3772622.png'
</script>

<template>
  <MainLayout>
    <div class="w-full flex flex-col mb-20 min-h-screen">
      <div
        class="relative bg-cover bg-center"
        :style="{ backgroundImage: `url(${backgroundImage})` }"
      >
        <!-- Dark Overlay -->
        <div class="absolute inset-0 bg-black opacity-50"></div>

        <!-- Content Layer -->
        <div
          class="relative text-white flex px-16 py-32 flex-grow flex-col gap-y-4 items-start"
        >
          <div class="tracking-[3px] uppercase leading-5">
            <span
              ><span class="font-medium">Posted on </span
              ><span class="font-black">startup</span></span
            >
          </div>
          <div class="[max-width:800px] pt-2 pl-px self-stretch">
            <div
              class="tracking-[-2px] leading-[64px] text-[56px] font-bold items-center flex"
            >
              <p>Step-by-step guide to choosing great font pairs</p>
            </div>
          </div>
          <div class="tracking-[0px] pt-2 leading-7">
            <span
              ><span class="text-blue-600"
                ><span class="text-white">By </span>James West</span
              >
              |<span class="whitespace-pre-wrap"> May 23, 2022</span></span
            >
          </div>
          <div class="tracking-[0px] w-[599px] leading-7 items-start flex">
            <p>
              Duis aute irure dolor in reprehenderit in voluptate velit esse
              cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
              cupidatat non proident.
            </p>
          </div>
          <div class="flex pt-8 items-end">
            <Button text="Read More &gt;" />
          </div>
        </div>
      </div>
    </div>

    <div class="flex w-full px-12 mb-20">
      <!-- Bagian Featured Post (Kiri) -->
      <div class="w-3/5 p-4">
        <h2 class="text-2xl font-bold mb-4">Featured Post</h2>
        <div class="p-8 border-gray-200 border">
          <img
            src="../assets/images/white-concrete-building-1838640.png"
            alt="Featured Post"
            loading="lazy"
            class="w-full h-96 object-cover mb-7"
          />
          <p class="text-sm mb-4">By John Deo | Aug 23, 2021</p>
          <h2 class="font-semibold text-xl mb-2">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus
            dolorem beatae ratione reprehenderit accusamus incidunt?
          </h2>
          <p class="font-thin text-gray-500 mb-4">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Natus
            error, esse tenetur iusto molestias quos expedita delectus.
          </p>
          <Button text="Read More &gt" />
        </div>
      </div>

      <!-- Bagian All Post (Kanan) -->
      <div class="w-2/5 p-4">
        <div class="mb-4 flex flex-row items-center">
          <h2 class="text-2xl font-bold">All Posts</h2>
          <a
            href="#"
            class="text-blue-600 hover:underline ml-auto hover:text-yellow-500 transition duration-200"
            >View All</a
          >
        </div>

        <div>
          <PostCard />
          <PostCard />
          <PostCard />
          <PostCard />
        </div>
      </div>
    </div>
    <div class="flex flex-col mx-16">
      <img
        loading="lazy"
        src="@/assets/images/misc/bar.svg"
        alt=""
        class="object-contain self-end aspect-[45.45] max-w-[1061px] w-[1061px] max-md:max-w-full"
      />
      <div class="px-20 py-24 w-full bg-gray-100 max-md:px-5 max-md:max-w-full">
        <div class="flex gap-5 max-md:flex-col">
          <div class="flex flex-col w-6/12 max-md:ml-0 max-md:w-full">
            <div
              class="flex flex-col grow text-base font-bold text-gray-800 max-md:mt-10 max-md:max-w-full"
            >
              <h2
                class="self-start font-semibold leading-none uppercase tracking-[3px]"
              >
                ABOUT US
              </h2>
              <h3
                class="mt-6 text-4xl tracking-tighter leading-10 max-md:max-w-full"
              >
                We are a community of content writers who share their learnings
              </h3>
              <p
                class="mt-4 mr-6 leading-7 text-zinc-500 max-md:mr-2.5 max-md:max-w-full font-thin"
              >
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
              <a
                href="#"
                class="self-start mt-7 text-lg leading-8 text-blue-600 hover:underline hover:text-yellow-500 transition duration-200"
                >Read More &gt;</a
              >
            </div>
          </div>
          <div class="flex flex-col ml-5 w-6/12 max-md:ml-0 max-md:w-full">
            <div
              class="flex flex-col items-start text-base text-gray-800 max-md:mt-10 max-md:max-w-full"
            >
              <h2 class="font-semibold leading-none uppercase tracking-[3px]">
                Our mission
              </h2>
              <h3 class="mt-6 text-3xl font-bold tracking-tighter leading-10">
                Creating valuable content for creatives all around the world
              </h3>
              <p
                class="self-stretch mt-4 leading-7 text-zinc-500 max-md:max-w-full"
              >
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="max-w-[1440px] mx-16 py-16">
      <h2 class="text-3xl font-semibold text-center mb-8">Choose A Category</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
        <CategoryCard
          title="Business"
          description="Deskripsi singkat untuk kategori 1."
          ><img
            src="../assets/images/icon/Icon.png"
            alt=""
            loading="lazy"
            class="w-10 h-auto bg-gray-100 border rounded-lg"
        /></CategoryCard>
        <CategoryCard
          title="Startup"
          description="Deskripsi singkat untuk kategori 2."
          ><img
            src="../assets/images/icon/Icon2.png"
            alt=""
            loading="lazy"
            class="w-10 h-auto bg-gray-100 border rounded-lg"
        /></CategoryCard>
        <CategoryCard
          title="Economy"
          description="Deskripsi singkat untuk kategori 3."
          ><img
            src="../assets/images/icon/icon3.png"
            alt=""
            loading="lazy"
            class="w-10 h-auto bg-gray-100 border rounded-lg"
        /></CategoryCard>
        <CategoryCard
          title="Technology"
          description="Deskripsi singkat untuk kategori 4."
          ><img
            src="../assets/images/icon/icon4.png"
            alt=""
            loading="lazy"
            class="w-10 h-auto bg-gray-100 border rounded-lg"
        /></CategoryCard>
      </div>
    </div>
    <div class="relative max-w-[1440px] mx-16 py-16">
      <!-- Foto -->
      <img
        src="../assets/images/close-up-photography-of-man-wearing-sunglasses-1212984.png"
        alt="Why We Started"
        class="w-[840px] h-auto"
      />

      <!-- Div Informasi -->
      <div class="absolute top-52 left-1/2 bg-white p-10">
        <h2 class="text-xl font-semibold mb-2">WHY WE STARTED</h2>
        <h1 class="text-4xl font-bold mb-2">
          It started out as a simple idea and evolved into our passion
        </h1>
        <p class="text-sm font-thin">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Commodi
          repellat eveniet perferendis eligendi laudantium! Excepturi, obcaecati
          repudiandae. Laudantium ratione delectus neque magnam, error, adipisci
          voluptatum rerum, placeat suscipit ipsum numquam?
        </p>
        <Button class="my-8" text="Discover Our Story" />
      </div>
    </div>
    <div class="max-w-[1440px] mx-16 py-16">
      <h2 class="text-2xl font-bold mb-8 text-center">List of Author</h2>

      <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
        <AuthorCard name="Author Name 1" position="Position 1"
          ><img
            src="src/assets/images/man-in-yellow-button-up-shirt-wearing-black-framed-eyeglasses-7562313.png"
            loading="lazy"
            alt=""
            class="w-24 h-24 rounded-full mb-4"
        /></AuthorCard>

        <AuthorCard name="Author Name 2" position="Position 2"
          ><img
            src="src/assets/images/woman-in-white-and-black-striped-shirt-wearing-black-sunglasses-3671083.png"
            loading="lazy"
            alt=""
            class="w-24 h-24 rounded-full mb-4"
        /></AuthorCard>

        <AuthorCard name="Author Name 3" position="Position 3"
          ><img
            src="src/assets/images/fashion-woman-cute-shoes-5704849.png"
            loading="lazy"
            alt=""
            class="w-24 h-24 rounded-full mb-4"
        /></AuthorCard>

        <AuthorCard name="Author Name 4" position="Position 4"
          ><img
            src="src/assets/images/content-baker-with-delicious-puff-in-cafeteria-6205509.png"
            loading="lazy"
            alt=""
            class="w-24 h-24 rounded-full mb-4"
        /></AuthorCard>
      </div>
    </div>

    <div class="mx-16 flex gap-x-14 justify-center mb-20">
      <img
        src="@/assets/images/logo/Featured in.svg"
        alt=""
        loading="lazy"
        class="logo hover:grayscale hover:scale-110 transition-all duration-300"
      />
      <img
        src="@/assets/images/logo/Logo 1.svg"
        alt=""
        loading="lazy"
        class="logo hover:grayscale hover:scale-110 transition-all duration-300"
      />
      <img
        src="@/assets/images/logo/Logo 2.svg"
        alt=""
        loading="lazy"
        class="logo hover:grayscale hover:scale-110 transition-all duration-300"
      />
      <img
        src="@/assets/images/logo/Logo 3.svg"
        alt=""
        loading="lazy"
        class="logo hover:grayscale hover:scale-110 transition-all duration-300"
      />
      <img
        src="@/assets/images/logo/Logo 4.svg"
        alt=""
        loading="lazy"
        class="logo hover:grayscale hover:scale-110 transition-all duration-300"
      />
      <img
        src="@/assets/images/logo/Logo 5.svg"
        alt=""
        loading="lazy"
        class="logo hover:grayscale hover:scale-110 transition-all duration-300"
      />
    </div>

    <div class="mx-16 flex flex-row gap-8 bg-[floralwhite] py-10">
      <div class="border-r-2 px-10 my-16">
        <h1 class="tracking-[3px] uppercase font-semibold leading-5">
          TESTIMONIALS
        </h1>
        <h2
          class="tracking-[-2px] leading-[48px] font-sen w-[345px] font-bold text-4xl mb-2"
        >
          What people say about our blog
        </h2>
        <p class="leading-7">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor.
        </p>
      </div>

      <div class="w-[80%] p-10 flex flex-col gap-y-14">
        <div class="p-4 pl-2 pr-16">
          <h3 class="text-2xl font-bold">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </h3>
        </div>
        <div class="p-4 flex flex-row items-center gap-x-4">
          <div>
            <img src="@/assets/images/Profile picture.png" alt="" />
          </div>
          <div class="text-2xl font-bold w-[65%]">
            <h4>Jonathan Vallem</h4>
            <p class="text-zinc-500 leading-7">New York, USA</p>
          </div>
          <div>
            <img
              src="@/assets/images/icon/Back button.svg"
              alt=""
              loading="lazy"
              class="transition-transform duration-300 ease-in-out transform hover:scale-110 hover:filter hover:brightness-50"
            />
          </div>
          <div>
            <img
              src="@/assets/images/icon/Next button.svg"
              alt=""
              loading="lazy"
              class="transition-transform duration-300 ease-in-out transform hover:scale-110 hover:filter hover:brightness-50"
            />
          </div>
        </div>
      </div>
    </div>
    <Join />
  </MainLayout>
</template>
