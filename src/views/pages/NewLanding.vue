<script setup>
import NewNavbar from '@/components/landing/NewNavbar.vue';
import NewHero from '@/components/landing/NewHero.vue';
import NewFeatures from '@/components/landing/NewFeatures.vue';
import AiCapabilities from '@/components/landing/AiCapabilities.vue';
import Testimonials from '@/components/landing/Testimonials.vue';
import NewFooter from '@/components/landing/NewFooter.vue';
</script>

<template>
  <div class="min-h-screen bg-white">
    <NewNavbar />
    <NewHero />
    <NewFeatures />
    <AiCapabilities />
    <Testimonials />
    <NewFooter />
  </div>
</template>

<style>
/* Add any global styles for the landing page here */
:root {
  --primary-50: #f0f9ff;
  --primary-100: #e0f2fe;
  --primary-200: #bae6fd;
  --primary-300: #7dd3fc;
  --primary-400: #38bdf8;
  --primary-500: #0ea5e9;
  --primary-600: #0284c7;
  --primary-700: #0369a1;
  --primary-800: #075985;
  --primary-900: #0c4a6e;
  
  --secondary-50: #fff7ed;
  --secondary-100: #ffedd5;
  --secondary-200: #fed7aa;
  --secondary-300: #fdba74;
  --secondary-400: #fb923c;
  --secondary-500: #f97316;
  --secondary-600: #ea580c;
  --secondary-700: #c2410c;
  --secondary-800: #9a3412;
  --secondary-900: #7c2d12;
}

/* Add smooth scrolling to the entire page */
html {
  scroll-behavior: smooth;
}
</style>
