<template>
  <section class="px-6">
    <header
      class="section sm:mx-auto px-4 py-3.5 rounded-full shadow-md flex items-center justify-between bg-white sm:mx-4.5"
    >
      <img src="/logo.svg" alt="" />

      <nav class="sm:flex items-center gap-4 hidden">
        <!--Home-->
        <NuxtLink to="/" custom v-slot="{ isExactActive, navigate }">
          <button
            @click="navigate"
            :class="
              isExactActive
                ? 'py-3 px-7 border-b-2 border-primary text-primary font-semibold'
                : 'text-[#1F2A2A] p-3 hover:text-primary-800'
            "
          >
            Home
          </button>
        </NuxtLink>

        <!--About-->
        <div class="relative" ref="dropdownRef" >
          <button
            @mouseenter="open"
            class="flex gap-1.5 items-center py-3 px-7 text-[#1F2A2A] p-3 hover:text-primary-800"
          >
            About us

            <svg
              width="12"
              height="7"
              viewBox="0 0 12 7"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M6 4.45487L10.6669 0L12 1.27256L6 7L0 1.27256L1.33312 0L6 4.45487Z"
                fill="currentColor"
              />
            </svg>
          </button>

          <div
            v-show="dropdownOpen"
            class="absolute mt-2 w-40 bg-white shadow rounded p-2"
          >
          <ul class="list-none space-y-1.5">
            <li>
              <a href="#who_we_are" class="rounded-sm hover:bg-primary-700 p-2.5 text hover:text-white text-sm w-full! block">
                Who we are
              </a>
            </li>
             <li>
              <a href="#strategy" class="rounded-sm hover:bg-primary-700 p-2.5 text hover:text-white text-sm w-full! block">
              Our Strategy Focus
              </a>
            </li>
             <li>
              <a href="#programs" class="rounded-sm hover:bg-primary-700 p-2.5 text hover:text-white text-sm w-full! block">
                Programme Areas
              </a>
            </li>
             <li>
              <a href="#flagship" class="rounded-sm hover:bg-primary-700 p-2.5 text hover:text-white text-sm w-full! block">
                Flagship Initiatives
              </a>
            </li>
             <li>
              <a href="#impact" class="rounded-sm hover:bg-primary-700 p-2.5 text hover:text-white text-sm w-full! block">
                Our Impact
              </a>
            </li>
             <li>
              <a href="#structure" class="rounded-sm hover:bg-primary-700 p-2.5 text hover:text-white text-sm w-full! block">
               Our Structure
              </a>
            </li>

            <li>
              <a href="#team" class="rounded-sm hover:bg-primary-700 p-2.5 text hover:text-white text-sm w-full! block">
              The Team
              </a>
            </li>

          </ul>
          </div>
        </div>

        <!--Blog-->
        <NuxtLink to="/blog" custom v-slot="{ isExactActive, navigate }">
          <button
            @click="navigate"
            :class="
              isExactActive
                ? 'py-3 px-7 border-b-2 border-primary text-primary font-semibold'
                : 'text-[#1F2A2A] p-3 hover:text-primary-800'
            "
          >
            Blog
          </button>
        </NuxtLink>

        <!--Media-->
        <NuxtLink to="/media" custom v-slot="{ isExactActive, navigate }">
          <button
            @click="navigate"
            :class="
              isExactActive
                ? 'py-3 px-7 border-b-2 border-primary text-primary font-semibold'
                : 'text-[#1F2A2A] p-3 hover:text-primary-800'
            "
          >
            Media
          </button>
        </NuxtLink>
      </nav>

      <!--Mobile Navbar-->
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
              <button
                @click="isOpen = false"
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

            <a href="#contact" class="secondary-btn w-fit ml-auto py-2!"
              >Contact Us</a
            >
          </div>
        </div>

        <a href="#contact" class="secondary-btn">Contact Us</a>
      </div>
    </header>
  </section>
</template>

<script setup>
import { ref, watch, onMounted, onBeforeUnmount } from "vue";

const isOpen = ref(false);
const dropdownOpen = ref(false);
let timeout = null;

watch(isOpen, (val) => {
  document.body.style.overflow = val ? "hidden" : "";
});

const open = () => {
  clearTimeout(timeout);
  dropdownOpen.value = true;
};

const close = () => {
  timeout = setTimeout(() => {
    dropdownOpen.value = false;
  }, 150);
};

const dropdownRef = ref(null);

const handleClickOutside = (event) => {
  if (!dropdownRef.value) return;

  if (!dropdownRef.value.contains(event.target)) {
    close();
  }
};

onMounted(() => {
  document.addEventListener("mousedown", handleClickOutside);
});

onBeforeUnmount(() => {
  document.removeEventListener("mousedown", handleClickOutside);
});
</script>
