<template>
  <header class="bg-white shadow-sm">
    <div class="container mx-auto px-4 py-6">
      <div class="flex items-center justify-between">
        <!-- Left side: Logo and Company Info -->
        <div class="flex items-center space-x-4">
          <!-- Logo Icon -->
          <div class="flex-shrink-0">
            <div class="w-16 h-16 bg-blue-500 rounded-lg flex items-center justify-center">
              <svg class="w-10 h-10 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
              </svg>
            </div>
          </div>
          
          <!-- Company Name and Tagline -->
          <div>
            <h1 class="text-2xl font-bold text-blue-600 uppercase tracking-tight">
              LEGACY SOLUTIONS, LLC
            </h1>
            <p class="text-sm text-gray-500 mt-1">
              24/7 Solutions for all your Business & Personal Service Needs
            </p>
          </div>
        </div>

        <!-- Right side: Contact Information -->
        <div class="flex items-center space-x-4">
          <div class="flex items-center space-x-3">
            <!-- Phone Icon -->
            <div class="w-12 h-12 bg-orange-500 rounded-full flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
              </svg>
            </div>
            
            <!-- Contact Text and Phone Number -->
            <div>
              <p class="text-sm text-gray-600 font-medium">Have Any Questions</p>
              <a href="tel:504-638-9090" class="text-2xl font-bold text-blue-600 hover:text-blue-700 transition-colors">
                504-638-9090
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HeaderComponent',
});
</script>

<style scoped>
/* Additional custom styles if needed */
</style>
