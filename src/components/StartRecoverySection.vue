<template>
  <section class="bg-white py-8 md:py-[60px]">
    <div class="container max-w-7xl mx-auto">
      <div class="flex flex-col md:flex-row md:items-center md:justify-between flex-wrap">
        <!-- Left Column: Text Content -->
        <div class="basis-[59.214%] p-[10px] flex flex-col gap-5 order-2 md:order-1">
          <h2 class="text-2xl md:text-4xl font-bold uppercase" style="color: #00274D;">
            START YOUR RECOVERY TODAY
          </h2>

          <p class="text-[16px] mb-[18px] text-gray-700 leading-relaxed">
            You've seen what's possible—recoveries of $16,000, $32,000, $58,000, even $78,000 from property settlements, insurance payouts, 401(k)s, inheritances, and other forgotten assets.
          </p>

          <p class="text-[16px] mb-[18px] text-gray-700 leading-relaxed">
            The process is quick, secure, and designed to save you time. Once you complete the short form below, our verification team reviews your information to confirm eligibility. If additional details are needed, you'll receive a message by text, email, or phone. Once verified, your recovery moves forward automatically under the authority of your signed agreement.
          </p>

          <p class="text-[16px] mb-[18px] text-gray-700 leading-relaxed">
            There's no risk and no upfront payment required. Legacy Solutions LLC is committed to making the process as effortless as possible. Whether you're located in one of Louisiana's 64 parishes or anywhere in the U.S., our team ensures your claim is handled efficiently and professionally.
          </p>
        </div>

        <!-- Right Column: Image -->
        <div class="basis-[40%] p-[10px] order-1 md:order-2">
          <img 
            src="/images/Start-recovery-section/UNCLAIMED-FUNDS-COULD-BE-WAITING-1-1-1.png" 
            alt="People shaking hands"
            class="w-full max-w-md h-auto object-contain rounded-lg"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'StartRecoverySection',
});
</script>

<style scoped>
</style>
