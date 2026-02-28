<template>
  <section class="relative bg-white overflow-hidden min-h-[600px]">
    <!-- Background Elements -->
    <div class="absolute inset-0 z-0">
      <!-- Background image covering the entire section -->
      <img 
        src="/images/Hero-section/Hero-Section-Banner.png" 
        alt="Background" 
        class="w-full h-full object-cover position-center"
      />
    </div>

    <div class="container max-w-7xl mx-auto px-4 py-8 md:py-16 relative z-10">
      <div class="flex flex-col md:grid md:grid-cols-2 gap-8 md:gap-12 items-center">
        <!-- Mobile: Image First, Desktop: Image Right -->
        <div class="flex justify-center md:justify-end order-1 md:order-2 w-full">
          <img 
            src="/images/Hero-section/Lousiana-Family-New1.png" 
            alt="Happy family with check" 
            class="w-full max-w-lg h-auto object-contain"
          />
        </div>

        <!-- Mobile: Text Second, Desktop: Text Left -->
        <div class="space-y-6 relative z-10 order-2 md:order-1 text-center md:text-left">
          <h1 class="text-3xl md:text-5xl lg:text-6xl font-bold leading-tight" style="color: #00274D;">
            CLAIM WHAT'S YOURS TODAY
          </h1>
          
          <p class="text-base md:text-lg text-gray-700 leading-relaxed">
            Serving all 64 Louisiana parishes and helping clients nationwide. Whether your unclaimed funds are tied to a Louisiana property or another state, our experienced team can help recover what's rightfully yours.
          </p>
          
          <div class="flex justify-center md:justify-start">
            <button class="bg-orange-500 hover:bg-orange-600 text-white font-bold uppercase px-6 md:px-8 py-3 md:py-4 rounded-lg transition-colors text-base md:text-lg shadow-lg">
              START MY FREE FUNDS CHECK
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HeroSection',
});
</script>

<style scoped>
/* Additional custom styles if needed */
</style>
