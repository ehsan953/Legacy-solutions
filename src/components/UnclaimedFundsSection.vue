<template>
  <section class="bg-white py-8 md:py-16">
    <div class="container max-w-7xl mx-auto px-4">
      <div class="flex flex-col md:grid md:grid-cols-2 gap-8 md:gap-12">
        <!-- Mobile: Image First, Desktop: Image Left -->
        <div class="flex justify-center md:justify-start order-1 w-full">
          <img 
            src="/images/Unclaimed-funds-section/UNCLAIMED-FUNDS-COULD-BE-WAITING-copy.png" 
            alt="Hands holding money and check" 
            class="w-full max-w-lg h-auto object-contain"
          />
        </div>

        <!-- Mobile: Text Second, Desktop: Text Right -->
        <div class="space-y-6 order-2">
          <!-- Icon -->
          <div class="flex justify-center md:justify-start">
            <div class="w-16 h-16 rounded-full flex items-center justify-center flex-shrink-0" style="background-color: #00274D;">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z" />
              </svg>
              <span class="text-white font-bold text-xl ml-1">$</span>
            </div>
          </div>

          <h2 class="text-2xl md:text-4xl lg:text-5xl font-bold uppercase leading-tight text-center md:text-left" style="color: #00274D;">
            UNCLAIMED FUNDS COULD BE WAITING FOR YOU
          </h2>

          <p class="text-base md:text-lg text-gray-700 leading-relaxed text-center md:text-left">
            Across all 64 Louisiana parishes and nationwide, thousands of people every year have money sitting unclaimed from property settlements, forgotten bank accounts, insurance payouts, 401(k) balances, inheritances, and other transactions. Many never realize these funds exist because records change and the process can feel overwhelming. At Legacy Solutions LLC, we make it simple to find and recover what's rightfully yours. Our team of experienced researchers and specialists use advanced tracking methods to locate eligible funds and guide you through a secure recovery process that requires no upfront costs.
          </p>

          <h3 class="text-xl md:text-3xl font-bold uppercase mt-6 md:mt-8 text-center md:text-left" style="color: #00274D;">
            UNCLAIMED FUNDS COULD BE WAITING FOR YOU.
          </h3>

          <p class="text-base md:text-lg text-gray-700 leading-relaxed text-center md:text-left">
            Our mission is straightforward. We help you recover your money without stress or confusion. Most steps can be completed online for your convenience. If we need additional information or a notarized form, our team will reach out personally by phone, email, or text to keep the process moving smoothly.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'UnclaimedFundsSection',
});
</script>

<style scoped>
/* Additional custom styles if needed */
</style>
