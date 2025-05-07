<script setup>
import { ref } from 'vue';

const mobileMenuOpen = ref(false);

const toggleMobileMenu = () => {
  mobileMenuOpen.value = !mobileMenuOpen.value;
};
</script>

<template>
  <nav class="bg-white border-b border-gray-100 px-6 py-4 fixed w-full z-50">
    <div class="max-w-7xl mx-auto flex justify-between items-center">
      <!-- Logo -->
      <div class="flex items-center">
        <a href="#" class="text-2xl font-bold text-gray-900">
          <span class="text-primary-500">Aivarium</span>
        </a>
      </div>

      <!-- Desktop Navigation -->
      <div class="hidden md:flex items-center space-x-8">
        <a href="#" class="text-gray-600 hover:text-primary-500 font-medium">Product</a>
        <a href="#" class="text-gray-600 hover:text-primary-500 font-medium">Solutions</a>
        <a href="#" class="text-gray-600 hover:text-primary-500 font-medium">Learn</a>
        <a href="#" class="text-gray-600 hover:text-primary-500 font-medium">Customers</a>
        <a href="#" class="text-gray-600 hover:text-primary-500 font-medium">Pricing</a>
      </div>

      <!-- CTA Buttons -->
      <div class="hidden md:flex items-center space-x-4">
        <a href="/auth/login" class="text-gray-600 hover:text-primary-500 font-medium">Log in</a>
        <a href="#waitlist" class="bg-primary-500 text-white px-4 py-2 rounded-md font-medium hover:bg-primary-600 transition-colors">
          Join Waitlist
        </a>
      </div>

      <!-- Mobile menu button -->
      <div class="md:hidden flex items-center">
        <button @click="toggleMobileMenu" class="text-gray-500 hover:text-gray-600 focus:outline-none">
          <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path v-if="!mobileMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
            <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
          </svg>
        </button>
      </div>
    </div>

    <!-- Mobile Menu -->
    <div v-show="mobileMenuOpen" class="md:hidden bg-white absolute left-0 right-0 shadow-md z-20 py-2 px-4 mt-4">
      <a href="#" class="block py-2 text-gray-600 hover:text-primary-500 font-medium">Product</a>
      <a href="#" class="block py-2 text-gray-600 hover:text-primary-500 font-medium">Solutions</a>
      <a href="#" class="block py-2 text-gray-600 hover:text-primary-500 font-medium">Learn</a>
      <a href="#" class="block py-2 text-gray-600 hover:text-primary-500 font-medium">Customers</a>
      <a href="#" class="block py-2 text-gray-600 hover:text-primary-500 font-medium">Pricing</a>
      <div class="border-t border-gray-200 my-2"></div>
      <a href="/auth/login" class="block py-2 text-gray-600 hover:text-primary-500 font-medium">Log in</a>
      <a href="#waitlist" class="block py-2 text-primary-500 font-medium">Join Waitlist</a>
    </div>
  </nav>
</template>
