<!-- app/app.vue -->
<template>
  <div>
    <NuxtPage />
  </div>
</template>

<script setup>
import { onMounted } from 'vue';

onMounted(async () => {
  const AOS = (await import('aos')).default;
  await import('aos/dist/aos.css');
  AOS.init({ once: false, duration: 800 });
});
</script>