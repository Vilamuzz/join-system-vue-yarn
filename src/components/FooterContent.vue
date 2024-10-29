<script setup lang="ts">
import Logo from '../assets/Logo.vue'
import Button from '../components/Button.vue'
</script>

<template>
  <footer
    class="pt-12 bg-slate-800 text-white w-full flex pb-14 flex-col gap-y-12 px-16"
  >
    <!-- Logo and Navigation Links -->
    <div class="flex flex-wrap justify-between items-center gap-y-6 gap-x-6">
      <div class="flex items-center">
        <Logo class="h-7 w-36" />
      </div>
      <nav
        class="flex flex-wrap justify-center items-center gap-x-6 gap-y-3 text-base"
      >
        <a href="#home" class="hover:underline">Home</a>
        <a href="#blog" class="hover:underline">Blog</a>
        <a href="#about" class="hover:underline">About us</a>
        <a href="#contact" class="hover:underline">Contact us</a>
        <a href="#privacy" class="hover:underline">Privacy Policy</a>
      </nav>
    </div>

    <!-- Subscription Section -->
    <div
      class="bg-white/10 w-full py-16 px-8 flex flex-col md:flex-row justify-between items-center font-bold"
    >
      <!-- Left side with description -->
      <p class="text-3xl mb-6 md:mb-0 md:text-left md:w-1/2">
        Subscribe to our newsletter to get the latest updates and news
      </p>

      <!-- Right side with form -->
      <div
        class="flex flex-col sm:flex-row gap-4 items-center w-full max-w-md md:w-1/2"
      >
        <input
          type="email"
          placeholder="Enter Your Email"
          class="border border-neutral-600 p-4 w-full text-gray-700 placeholder-gray-500 bg-white/10"
        />
        <Button text="Subscribe" />
      </div>
    </div>

    <!-- Contact Information and Social Media Links -->
    <div class="flex flex-wrap justify-between items-start gap-y-4 gap-x-6">
      <div class="text-sm">
        <p>Finstreet 118, 2561 Fintown</p>
        <p>
          <a href="mailto:Hello@finsweet.com" class="hover:underline"
            >Hello@finsweet.com</a
          >
          | 020 7993 2905
        </p>
      </div>
      <div class="flex gap-4">
        <a
          href="https://facebook.com"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Facebook"
        >
          <img
            class="h-4 w-full"
            src="../assets/images/logo/FacebookNegative.png"
            loading="lazy"
          />
        </a>
        <a
          href="https://twitter.com"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Twitter"
        >
          <img
            class="h-4 w-full"
            src="../assets/images/logo/TwitterNegative.png"
            loading="lazy"
          />
        </a>
        <a
          href="https://instagram.com"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Instagram"
        >
          <img
            class="h-4 w-full"
            src="../assets/images/logo/InstagramNegative.png"
            loading="lazy"
          />
        </a>
        <a
          href="https://linkedin.com"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="LinkedIn"
        >
          <img
            class="h-4 w-full"
            src="../assets/images/logo/LinkedInNegative.png"
            loading="lazy"
          />
        </a>
      </div>
    </div>
  </footer>
</template>
