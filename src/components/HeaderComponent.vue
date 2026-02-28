<template>
  <header class="bg-white shadow-sm">
    <div class="container max-w-7xl mx-auto px-4 py-6">
      <div class="flex items-center justify-between">
        <!-- Left side: Logo -->
        <div class="flex items-center">
          <img 
            src="/images/logo/logo-legacy-updated-1024x433-1.png" 
            alt="Legacy Solutions LLC Logo" 
            class="h-16 w-auto object-contain"
          />
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
              <a href="tel:504-638-9090" class="text-xl md:text-2xl font-bold transition-colors hover:opacity-80" style="color: #00274D;">
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
