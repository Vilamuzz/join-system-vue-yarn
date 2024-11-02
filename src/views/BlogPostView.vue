<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import Join from '@/components/Join.vue'
</script>

<template>
  <MainLayout>
    <div class="mx-80 flex flex-col gap-y-4 mt-32 mb-14">
      <div class="flex flex-row gap-x-4 items-center">
        <div><img src="@/assets/images/Image.png" alt="" loading="lazy" /></div>
        <div>
          <h3 class="font-semibold text-xl text-yellow-300">Andrew Jonson</h3>
          <p>Posted on 27th January 2022</p>
        </div>
      </div>
      <h1 class="text-4xl font-bold">
        Step-by-step guide to choosing great font pairs
      </h1>
      <div class="flex flex-row gap-x-2 items-center">
        <div>
          <img
            src="@/assets/images/icon/Icon2.png"
            alt=""
            loading="lazy"
            class="rounded-full"
          />
        </div>
        <h3 class="font-semibold text-lg">Startup</h3>
      </div>
    </div>
    <div class="mx-16">
      <img
        src="@/assets/images/photo-of-woman-wearing-eyeglasses.png"
        alt=""
        loading="lazy"
        class="h-auto"
      />
    </div>
    <div class="mx-80 flex flex-col gap-y-4 mt-14">
      <h1 class="text-gray-700 text-2xl font-bold">
        Lorem ipsum dolor sit amet
      </h1>
      <p class="text-gray-500 mb-10">
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sequi ipsa
        tenetur eum explicabo, eveniet, praesentium ipsam possimus inventore, ab
        temporibus vel cupiditate laborum ex excepturi! Soluta, libero mollitia!
        Consequatur, vero!
      </p>
      <h1 class="text-gray-700 text-2xl font-bold">
        Lorem ipsum dolor sit amet
      </h1>
      <p class="text-gray-500">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam itaque
        ea libero mollitia quos repellendus quod nemo! Illum laboriosam, nam
        consectetur laborum dignissimos corrupti ipsa voluptatibus eaque!
        Obcaecati, labore vero?
        <br />
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consequatur
        nostrum voluptate eum velit odit aut neque magnam, corrupti possimus ea
        temporibus tenetur. Dolor eius quas accusantium molestiae est voluptate
        eaque.
      </p>
      <ul
        class="list-disc list-inside text-gray-700 space-y-2 text-lg font-bold"
      >
        <li>Lorem ipsum dolor sit amet</li>
        <li>Lorem ipsum dolor sit amet</li>
        <li>Lorem ipsum dolor sit amet</li>
      </ul>
      <p class="text-gray-500 mb-10">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae quod et
        ex quisquam cumque, facere quas provident corporis odio, neque nam nisi
        laborum dolore ullam voluptate voluptas, optio accusantium eaque!
      </p>

      <h1 class="text-gray-700 text-2xl font-bold">
        Lorem ipsum dolor sit amet
      </h1>
      <p class="text-gray-500">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quasi facilis
        error perspiciatis voluptatum dolorum sequi veniam, ea ullam
        necessitatibus sint repellendus est eaque id pariatur fuga voluptate
        quaerat possimus ex.
      </p>
    </div>
    <div class="mx-16 my-24 flex flex-col space-y-4">
      <h1 class="text-3xl font-bold">What to read next</h1>
      <div class="flex flex-row space-x-6">
        <div class="flex flex-col w-1/3 space-y-4">
          <img
            src="@/assets/images/photo-of-people-doing-handshakes-3183197.png"
            alt=""
            loading="lazy"
          />
          <div class="font-medium leading-5 text-sm">
            <span class="text-neutral-600">By </span>
            <span class="text-yellow-300">John Doe </span>
            <span class="text-neutral-600">| May 23, 2022</span>
          </div>
          <h1 class="text-xl font-semibold">
            A UX Case Study Creating a Studious Environment for Students:
          </h1>
          <p class="text-gray-500">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quasi
            facilis error perspiciatis voluptatum dolorum sequi veniam, ea ullam
            necessitatibus sint repellendus est eaque id pariatur fuga voluptate
            quaerat possimus ex.
          </p>
        </div>

        <div class="flex flex-col w-1/3 space-y-4">
          <img
            src="@/assets/images/photo-of-people-doing-handshakes-3183197.png"
            alt=""
            loading="lazy"
          />
          <div class="font-medium leading-5 text-sm">
            <span class="text-neutral-600">By </span>
            <span class="text-yellow-300">John Doe </span>
            <span class="text-neutral-600">| May 23, 2022</span>
          </div>
          <h1 class="text-xl font-semibold">
            A UX Case Study Creating a Studious Environment for Students:
          </h1>
          <p class="text-gray-500">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quasi
            facilis error perspiciatis voluptatum dolorum sequi veniam, ea ullam
            necessitatibus sint repellendus est eaque id pariatur fuga voluptate
            quaerat possimus ex.
          </p>
        </div>

        <div class="flex flex-col w-1/3 space-y-4">
          <img
            src="@/assets/images/photo-of-people-doing-handshakes-3183197.png"
            alt=""
            loading="lazy"
          />
          <div class="font-medium leading-5 text-sm">
            <span class="text-neutral-600">By </span>
            <span class="text-yellow-300">John Doe </span>
            <span class="text-neutral-600">| May 23, 2022</span>
          </div>
          <h1 class="text-xl font-semibold">
            A UX Case Study Creating a Studious Environment for Students:
          </h1>
          <p class="text-gray-500">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quasi
            facilis error perspiciatis voluptatum dolorum sequi veniam, ea ullam
            necessitatibus sint repellendus est eaque id pariatur fuga voluptate
            quaerat possimus ex.
          </p>
        </div>
      </div>
    </div>
    <div class="h-[2px] mx-16 bg-gray-300"></div>
    <Join />
  </MainLayout>
</template>
