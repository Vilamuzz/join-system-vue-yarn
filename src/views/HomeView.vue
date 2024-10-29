<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import Button from '@/components/Button.vue'
import Category from '@/components/Category.vue'
import Join from '@/components/Join.vue'
</script>

<template>
  <MainLayout>
    <div class="w-full flex flex-col mb-20">
      <div
        class="before:[transform:scaleY(-1)_rotate(-180deg)] before:[background-position: center] before:[background-size:cover] before:[content:''] flex flex-grow flex-col max-h-full max-w-full z-0 relative before:z-[-1] before:bg-[url('@/assets/images/man-in-black-suit-wearing-eye-glasses-sitting-on-gray-sofa-using-macbook-3772622.png')] before:bg-no-repeat before:absolute before:inset-0"
      >
        <div
          class="font-inter pr-[556px] bg-[radial-gradient(transparent,_#00000099)] text-white flex pt-32 pl-20 pb-48 flex-grow flex-col gap-y-4 items-start"
        >
          <div class="tracking-[3px] uppercase leading-5">
            <span
              ><span class="font-medium">Posted on </span>
              <span class="font-black">startup</span></span
            >
          </div>
          <div class="[max-width:804px] pt-2 pl-px self-stretch">
            <div
              class="tracking-[-2px] leading-[64px] text-[56px] font-sen font-bold items-center flex"
            >
              <p>Step-by-step guide to choosing great font pairs</p>
            </div>
          </div>
          <div class="tracking-[0px] pt-2 leading-7">
            <span
              ><span class="text-blue-600"
                ><span class="text-white">By </span>
                James West
                <span class="text-white"
              /></span>
              <span class="whitespace-pre-wrap">
                {{ '  May 23, 2022' }}</span
              ></span
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
            <Button text="Read More &gt" />
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
          <div class="p-6 mb-2 transition duration-300 hover:bg-yellow-100">
            <p class="text-sm">By John Deo | Aug 23, 2021</p>
            <h3 class="font-semibold">
              8 Figma design systems that you can download for free today.
            </h3>
          </div>
          <div class="p-6 mb-2 transition duration-300 hover:bg-yellow-100">
            <p class="text-sm">By John Deo | Aug 23, 2021</p>
            <h3 class="font-semibold">
              8 Figma design systems that you can download for free today.
            </h3>
          </div>
          <div class="p-6 mb-2 transition duration-300 hover:bg-yellow-100">
            <p class="text-sm">By John Deo | Aug 23, 2021</p>
            <h3 class="font-semibold">
              8 Figma design systems that you can download for free today.
            </h3>
          </div>
          <div class="p-6 mb-2 transition duration-300 hover:bg-yellow-100">
            <p class="text-sm">By John Deo | Aug 23, 2021</p>
            <h3 class="font-semibold">
              8 Figma design systems that you can download for free today.
            </h3>
          </div>
        </div>
      </div>
    </div>
    <div class="flex flex-col mx-16">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/c70f7be6c65e1aeb76cee8cd48a5a2cb205679fe0a4c6afe3ea9f80564c9ec4e?placeholderIfAbsent=true&apiKey=cc987fc235b043cdb56f509dedbe3ab1"
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
      <Category />
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
        <div class="flex flex-col items-center bg-gray-200 p-6">
          <img
            src="../assets/images/man-in-yellow-button-up-shirt-wearing-black-framed-eyeglasses-7562313.png"
            alt="Author 1"
            class="w-24 h-24 rounded-full mb-4"
          />
          <h3 class="text-lg font-semibold">Author Name 1</h3>
          <p class="text-sm text-gray-600">Position 1</p>
          <div class="flex space-x-2 mt-2">
            <a href="#" class="text-blue-600">Twitter</a>
            <a href="#" class="text-blue-600">LinkedIn</a>
          </div>
        </div>

        <div class="flex flex-col items-center bg-gray-200 p-6">
          <img
            src="../assets/images/woman-in-white-and-black-striped-shirt-wearing-black-sunglasses-3671083.png"
            alt="Author 2"
            class="w-24 h-24 rounded-full mb-4"
          />
          <h3 class="text-lg font-semibold">Author Name 2</h3>
          <p class="text-sm text-gray-600">Position 2</p>
          <div class="flex space-x-2 mt-2">
            <a href="#" class="text-blue-600">Twitter</a>
            <a href="#" class="text-blue-600">LinkedIn</a>
          </div>
        </div>

        <div class="flex flex-col items-center bg-gray-200 p-6">
          <img
            src="../assets/images/fashion-woman-cute-shoes-5704849.png"
            alt="Author 3"
            class="w-24 h-24 rounded-full mb-4"
          />
          <h3 class="text-lg font-semibold">Author Name 3</h3>
          <p class="text-sm text-gray-600">Position 3</p>
          <div class="flex space-x-2 mt-2">
            <a href="#" class="text-blue-600">Twitter</a>
            <a href="#" class="text-blue-600">LinkedIn</a>
          </div>
        </div>

        <div class="flex flex-col items-center bg-gray-200 p-6">
          <img
            src="../assets/images/content-baker-with-delicious-puff-in-cafeteria-6205509.png"
            alt="Author 4"
            class="w-24 h-24 rounded-full mb-4"
          />
          <h3 class="text-lg font-semibold">Author Name 4</h3>
          <p class="text-sm text-gray-600">Position 4</p>
          <div class="flex space-x-2 mt-2">
            <a href="#" class="text-blue-600">Twitter</a>
            <a href="#" class="text-blue-600">LinkedIn</a>
          </div>
        </div>
      </div>
    </div>
    <div class="max-w-[1440px] flex flex-col m-16">
      <div
        class="pb-[74px] bg-[floralwhite] flex justify-center pt-20 flex-grow items-center px-28"
      >
        <div
          class="min-[1270px]:flex-nowrap tracking-[0px] text-slate-800 flex flex-wrap justify-center h-80 flex-grow gap-x-20 gap-y-20 items-end"
        >
          <div class="flex pb-24 flex-col items-center">
            <div class="font-inter w-[349px] flex flex-col gap-y-3 items-start">
              <div class="tracking-[3px] uppercase font-semibold leading-5">
                TESTIMONIALs
              </div>
              <div
                class="tracking-[-2px] leading-[48px] font-sen w-[345px] font-bold text-4xl items-start flex"
              >
                <p>What people say about our blog</p>
              </div>
              <div class="[max-width:349px] pt-1 self-stretch">
                <div class="leading-7 items-center flex">
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <Line class="[min-height:310px] flex-shrink-0 h-80 w-px" />
          <div
            class="min-[1270px]:flex-nowrap pl-[15px] flex flex-wrap justify-center gap-x-px gap-y-px items-end"
          >
            <div class="flex pb-px flex-col items-center">
              <div
                class="font-sen w-[469px] gap-y-[121px] font-bold leading-8 text-2xl flex flex-col items-start"
              >
                <div class="items-start flex self-stretch">
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua.
                  </p>
                </div>
                <div
                  class="min-[1270px]:flex-nowrap flex flex-wrap gap-x-36 gap-y-6 items-start"
                >
                  <div class="flex justify-center gap-x-4 items-start">
                    <div
                      class="flex-shrink-0 flex h-12 w-12 flex-col items-center"
                    >
                      <ProfilePicture class="flex-shrink-0 h-12 w-12" />
                    </div>
                    <div class="flex flex-col items-center">
                      <div>
                        <div>Jonathan Vallem</div>
                        <div class="text-zinc-500 font-inter leading-7">
                          New york, USA
                        </div>
                      </div>
                    </div>
                  </div>
                  <BackButton class="flex-shrink-0 h-12 w-12" />
                </div>
              </div>
            </div>
            <div class="flex pb-1.5 flex-col items-center">
              <NextButton class="flex-shrink-0 h-16 w-16" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <Join />
  </MainLayout>
</template>
