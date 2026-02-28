<template>
  <section class="bg-white py-8 md:py-16">
    <div class="container max-w-7xl mx-auto px-4">
      <!-- Title -->
      <h2 class="text-2xl md:text-4xl lg:text-5xl font-bold uppercase text-center mb-8 md:mb-12" style="color: #00274D;">
        WHY PEOPLE CHOOSE LEGACY SOLUTIONS
      </h2>

      <!-- Customer Images Grid (2x2 for both mobile and desktop) -->
      <div class="max-w-3xl mx-auto mb-8 md:mb-12">
        <!-- <div class="grid grid-cols-2 md:grid-cols-4 gap-4 md:gap-6"> -->
          <!-- Top Left: Couple making heart -->
          <div class="flex justify-center">
            <img 
              src="/images/Why-people-choose-section/WHY-PEOPLE-CHOOSE-LEGACY-SOLUTIONS-All.png" 
              alt="Happy couple making heart shape"
              class="w-full h-full object-cover"
            />
          </div>
          
        <!-- </div> -->
      </div>

      <!-- Call to Action -->
      <div class="text-center mb-8 md:mb-12">
        <p class="text-base md:text-lg lg:text-xl mb-4 md:mb-6 max-w-2xl mx-auto px-4" style="color: #00274D;">
          It takes just a minute to see if you qualify. Don't leave what's yours unclaimed another day.
        </p>
        <button class="bg-orange-500 hover:bg-orange-600 text-white font-bold uppercase px-6 md:px-8 py-3 md:py-4 rounded-lg transition-colors text-base md:text-lg shadow-lg">
          START MY FREE FUNDS CHECK
        </button>
      </div>

      <!-- Additional Features -->
      <!-- Desktop: Show all 4 features -->
      <div class="max-w-5xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-6 md:gap-8 text-center">
          <div class="flex items-center gap-2">
            <div class="w-12 h-12 rounded-full flex items-center justify-center" style="background-color: #00274D;">
              <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
              </svg>
              <span class="text-white font-bold text-sm ml-0.5">$</span>
            </div>
            <p class="text-sm text-gray-700">Fast eligibility confirmation and secure handling</p>
          </div>
          
          <div class="flex items-center gap-2">
            <div class="w-12 h-12 rounded-full flex items-center justify-center" style="background-color: #00274D;">
              <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
              </svg>
            </div>
            <p class="text-sm text-gray-700">Updates by phone, email, or text when needed</p>
          </div>
          
          <div class="flex items-center gap-2">
            <div class="w-12 h-12 rounded-full flex items-center justify-center" style="background-color: #00274D;">
              <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
              </svg>
            </div>
            <p class="text-sm text-gray-700">Serving all 64 Louisiana parishes and clients nationwide</p>
          </div>
          
          <div class="flex items-center gap-2">
            <div class="w-12 h-12 rounded-full flex items-center justify-center" style="background-color: #00274D;">
              <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
              </svg>
            </div>
            <p class="text-sm text-gray-700">Most steps completed online for speed and convenience</p>
          </div>
        </div>
        
        <!-- Separator Line -->
        <div class="mt-8 md:mt-12 flex justify-center">
          <div class="w-24 h-px bg-gray-300"></div>
        </div>
      </div>

    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'WhyPeopleChooseSection',
});
</script>

<style scoped>
/* Additional custom styles if needed */
</style>
