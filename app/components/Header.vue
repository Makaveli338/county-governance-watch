<template>
  <section class="px-6">
    <header
      class="section sm:mx-auto px-4 py-3.5 rounded-full shadow-md flex items-center justify-between bg-white sm:mx-4.5"
    >
      <img src="/logo.svg" alt="" />

      <nav class="sm:flex items-center gap-4 hidden">
        <NuxtLink
          v-for="link in navLinks"
          :key="link.to"
          :to="link.to"
          custom
          v-slot="{ isExactActive, navigate }"
        >
          <button
            @click="navigate"
            :class="
              isExactActive
                ? 'py-3 px-7 border-b-2 border-primary text-primary font-semibold'
                : 'text-[#1F2A2A] p-3 hover:text-primary-800'
            "
          >
            {{ link.label }}
          </button>
        </NuxtLink>
      </nav>

      <div class="flex gap-4 items-center">
        <div class="relative">
          <button @click="isOpen = !isOpen" class="block sm:hidden">
            <svg
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M2.5 10H17.5M2.5 5H17.5M2.5 15H17.5"
                stroke="#1F2A2A"
                stroke-width="1.3"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </button>

          <div
            v-if="isOpen"
            class="h-screen fixed w-50 top-0 right-0 bg-white shadow-lg rounded-lg py-10 px-3 z-50 space-y-4"
          >
            <div class="w-full items-start justify-between flex">
              <button @click="isOpen = false"
                class="bg-primary hover:bg-primary-300 cursor-pointer rounded-full p-1"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  class="size-5"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="m9.75 9.75 4.5 4.5m0-4.5-4.5 4.5M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"
                  />
                </svg>
              </button>

              <img src="/logo.svg" alt="" class="h-11" />
            </div>

            <div class="flex flex-col items-end ml-auto w-[60%] text-end">
              <NuxtLink
                v-for="link in navLinks"
                :key="link.to"
                :to="link.to"
                custom
                v-slot="{ isExactActive, navigate }"
              >
                <button
                  @click="navigate"
                  :class="
                    isExactActive
                      ? ' text-primary font-semibold py-2 px-4.5 border-b-2 border-primary w-full text-end'
                      : 'text-[#1F2A2A] p-3 hover:text-primary-800 py-2 px-4.5 w-full text-end'
                  "
                >
                  {{ link.label }}
                </button>
              </NuxtLink>
            </div>

            <a href="#contact" class="secondary-btn w-fit ml-auto py-2!">Contact Us</a>
          </div>
        </div>

        <a href="#contact" class="secondary-btn">Contact Us</a>
      </div>
    </header>
  </section>
</template>

<script setup>
import { ref, watch } from "vue";

const isOpen = ref(false);

watch(isOpen, (val) => {
  document.body.style.overflow = val ? "hidden" : "";
});

const navLinks = [
  { label: "Home", to: "/" },
  { label: "About us", to: "/about" },
  { label: "Blog", to: "/blog" },
  { label: "Media", to: "/media" },
];
</script>
