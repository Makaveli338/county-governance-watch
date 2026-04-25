<template>
  <header class="section mx-auto px-4 py-3.5 rounded-full shadow-md flex items-center justify-between bg-white">
    <img src="/logo.svg" alt="">

    <nav class="flex items-center gap-4">
      <NuxtLink
        v-for="link in navLinks"
        :key="link.to"
        :to="link.to"
        custom
        v-slot="{ isExactActive, navigate }"
      >
        <button
          @click="navigate"
          :class="isExactActive
            ? 'py-3 px-7 border-b-2 border-primary text-primary font-semibold'
            : 'text-[#1F2A2A] p-3 hover:text-primary-800'"
        >{{ link.label }}</button>
      </NuxtLink>
    </nav>

    <button class="secondary-btn">Contact us</button>
  </header>
</template>

<script setup>
const navLinks = [
  { label: 'Home', to: '/' },
  { label: 'About us', to: '/about' },
  { label: 'Blog', to: '/blog' },
  { label: 'Media', to: '/media' },
]
</script>
