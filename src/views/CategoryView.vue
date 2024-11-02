<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import Hero from '@/components/Hero.vue'
import CategoryCardView from '@/components/CategoryCardView.vue'
import CategoryListCard from '@/components/CategoryListCard.vue'
import Tag from '@/components/Tag.vue'
</script>
<template>
  <MainLayout>
    <Hero
      text="Business"
      subtext="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore."
      :showText="true"
      breadcrumb="Blog &gt; Business"
    />
    <div class="mx-16 my-24 flex flex-row justify-between">
      <div class="w-[70%] flex flex-col gap-y-10">
        <CategoryCardView />
        <CategoryCardView />
        <CategoryCardView />
        <CategoryCardView />
      </div>

      <div class="w-[30%] flex flex-col gap-y-8">
        <div class="p-5 items-start flex flex-col gap-y-4">
          <div
            class="tracking-[-2px] leading-[48px] text-slate-800 font-bold text-4xl mb-4"
          >
            <h1>Categories</h1>
          </div>
          <CategoryListCard title="Startup"
            ><img
              src="@/assets/images/icon/Icon2.png"
              alt=""
              class="w-10 h-auto bg-gray-100 border rounded-lg"
          /></CategoryListCard>
          <CategoryListCard title="Business"
            ><img
              src="@/assets/images/icon/Icon.png"
              alt=""
              class="w-10 h-auto bg-gray-100 border rounded-lg"
          /></CategoryListCard>
          <CategoryListCard title="Economy"
            ><img
              src="@/assets/images/icon/icon3.png"
              alt=""
              class="w-10 h-auto bg-gray-100 border rounded-lg"
          /></CategoryListCard>
          <CategoryListCard title="Technology"
            ><img
              src="@/assets/images/icon/icon4.png"
              alt=""
              class="w-10 h-auto bg-gray-100 border rounded-lg"
          /></CategoryListCard>
        </div>

        <div class="p-5 items-start flex flex-col gap-y-4">
          <div
            class="tracking-[-2px] leading-[48px] text-slate-800 font-bold text-4xl mb-4"
          >
            <h1>All Tags</h1>
          </div>

          <div class="flex flex-wrap gap-3 text-zinc-400">
            <Tag title="Business" />
            <Tag title="Experience" />
            <Tag title="Screen" />
            <Tag title="Technology" />
            <Tag title="Marketing" />
            <Tag title="Life" />
          </div>
        </div>
      </div>
    </div>
  </MainLayout>
</template>
