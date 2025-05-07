<script setup>
import { ref } from 'vue';

const email = ref('');
const isSubscribed = ref(false);
const receiveUpdates = ref(true);

const handleSubmit = () => {
  // Here you would typically send the email to your backend
  if (email.value) {
    isSubscribed.value = true;
    // Reset form
    setTimeout(() => {
      email.value = '';
      isSubscribed.value = false;
    }, 3000);
  }
};
</script>

<template>
  <div class="pt-24 bg-gradient-to-br from-white to-gray-50">
    <div class="max-w-7xl mx-auto px-6 lg:px-8">
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center py-16">
        <!-- Left column: Text content -->
        <div>
          <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 leading-tight">
            The data factory <br />
            for AI teams
          </h1>
          <p class="mt-6 text-lg md:text-xl text-gray-600 max-w-2xl">
            Aivarium delivers innovative services and software to operate,
            build, or staff your modern AI data factory
          </p>
          
          <!-- Waitlist Signup Section -->
          <div id="waitlist" class="mt-8 max-w-md">
            <h3 class="text-lg font-semibold mb-2">Join our waitlist</h3>
            <div v-if="!isSubscribed" class="flex flex-col space-y-3">
              <input 
                v-model="email" 
                type="email" 
                placeholder="Enter your email" 
                class="px-4 py-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-primary-500"
              />
              <div class="flex items-center">
                <input 
                  id="updates" 
                  v-model="receiveUpdates" 
                  type="checkbox" 
                  class="h-4 w-4 text-primary-500 focus:ring-primary-500 border-gray-300 rounded"
                />
                <label for="updates" class="ml-2 text-sm text-gray-600">
                  I'd like to receive product updates and news
                </label>
              </div>
              <button 
                @click="handleSubmit" 
                class="bg-primary-500 text-white px-6 py-3 rounded-md font-medium hover:bg-primary-600 transition-colors w-full md:w-auto"
              >
                Join Waitlist
              </button>
            </div>
            <div v-else class="text-green-600 font-medium py-3">
              Thank you! We'll notify you when we launch.
            </div>
          </div>
        </div>
        
        <!-- Right column: Image -->
        <div class="flex justify-center">
          <div class="relative">
            <!-- Placeholder for your hero image -->
            <div class="w-full h-80 md:h-96 lg:h-[500px] bg-gray-200 rounded-lg flex items-center justify-center">
              <span class="text-gray-500">Hero Image Placeholder</span>
            </div>
            
            <!-- Decorative elements -->
            <div class="absolute -top-4 -right-4 w-24 h-24 bg-primary-100 rounded-full opacity-70"></div>
            <div class="absolute -bottom-4 -left-4 w-16 h-16 bg-secondary-100 rounded-full opacity-70"></div>
          </div>
        </div>
      </div>
      
      <!-- Trusted by section -->
      <div class="py-12 border-t border-gray-100">
        <p class="text-center text-sm text-gray-500 mb-8">Trusted by companies of all sizes</p>
        <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-8 items-center justify-items-center opacity-70">
          <!-- Company logos placeholders -->
          <div class="h-8 w-24 bg-gray-200 rounded"></div>
          <div class="h-8 w-24 bg-gray-200 rounded"></div>
          <div class="h-8 w-24 bg-gray-200 rounded"></div>
          <div class="h-8 w-24 bg-gray-200 rounded"></div>
          <div class="h-8 w-24 bg-gray-200 rounded"></div>
          <div class="h-8 w-24 bg-gray-200 rounded"></div>
        </div>
      </div>
    </div>
  </div>
</template>
