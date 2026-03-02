<template>
  <section class="bg-white py-8 md:py-[60px]">
    <div class="container max-w-7xl mx-auto">

      <div class="flex flex-col md:flex-row flex-wrap">
        <!-- Left Column: FAQ Items -->
        <div class="basis-[60%] pl-[30px] pr-[20px] flex flex-col gap-5">
          <h2 class="text-2xl md:text-4xl font-bold uppercase" style="color: #00274D;">
            FREQUENTLY ASKED QUESTIONS
          </h2>
          <p class="text-[16px] text-gray-600 mb-[18px]">
            Common Questions, Straight Answers
          </p>
          <div>
            <!-- FAQ Item 1 -->
            <div class="bg-[#FAFBFC] rounded-lg border border-gray-200 p-5 mb-[10px]">
              <button 
                @click="toggleFAQ(0)"
                class="w-full flex items-center justify-between text-left"
              >
                <h3 class="text-[16px] font-semibold text-gray-900">
                  What does Legacy Solutions LLC do?
                </h3>
                <svg 
                  class="w-4 h-4 transition-transform" 
                  :class="{ 'rotate-45': openFAQ === 0 }"
                  style="color: #00274D;"
                  fill="none" 
                  stroke="currentColor" 
                  viewBox="0 0 24 24"
                >
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4" />
                </svg>
              </button>
              <div v-if="openFAQ === 0" class="mt-4 text-sm md:text-base text-gray-700">
                <p>Legacy Solutions LLC specializes in helping individuals recover unclaimed funds, including property settlements, forgotten bank accounts, insurance payouts, 401(k) balances, and inheritances. We handle the entire recovery process on your behalf.</p>
              </div>
            </div>
  
            <!-- FAQ Item 2 -->
            <div class="bg-[#FAFBFC] rounded-lg border border-gray-200 p-5 mb-[10px]">
              <button 
                @click="toggleFAQ(1)"
                class="w-full flex items-center justify-between text-left"
              >
                <h3 class="text-[16px] font-semibold text-gray-900">
                  How much does it cost?
                </h3>
                <svg 
                  class="w-4 h-4 transition-transform" 
                  :class="{ 'rotate-45': openFAQ === 1 }"
                  style="color: #00274D;"
                  fill="none" 
                  stroke="currentColor" 
                  viewBox="0 0 24 24"
                >
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4" />
                </svg>
              </button>
              <div v-if="openFAQ === 1" class="mt-4 text-sm md:text-base text-gray-700">
                <p>There are no upfront costs. Legacy Solutions LLC only gets paid when you receive your funds. Our success fee is deducted only after your claim is approved and you receive your check.</p>
              </div>
            </div>
  
            <!-- FAQ Item 3 -->
            <div class="bg-[#FAFBFC] rounded-lg border border-gray-200 p-5 mb-[10px]">
              <button 
                @click="toggleFAQ(2)"
                class="w-full flex items-center justify-between text-left"
              >
                <h3 class="text-[16px] font-semibold text-gray-900">
                  How long does the process take?
                </h3>
                <svg 
                  class="w-4 h-4 transition-transform" 
                  :class="{ 'rotate-45': openFAQ === 2 }"
                  style="color: #00274D;"
                  fill="none" 
                  stroke="currentColor" 
                  viewBox="0 0 24 24"
                >
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4" />
                </svg>
              </button>
              <div v-if="openFAQ === 2" class="mt-4 text-sm md:text-base text-gray-700">
                <p>Eligibility verification typically takes 24-48 hours. Once your agreement is signed, we begin the recovery process immediately. Most steps can be completed online, making the process fast and convenient.</p>
              </div>
            </div>
  
            <!-- FAQ Item 4 -->
            <div class="bg-[#FAFBFC] rounded-lg border border-gray-200 p-5 mb-[10px]">
              <button 
                @click="toggleFAQ(3)"
                class="w-full flex items-center justify-between text-left"
              >
                <h3 class="text-[16px] font-semibold text-gray-900">
                  Is my information secure?
                </h3>
                <svg 
                  class="w-4 h-4 transition-transform" 
                  :class="{ 'rotate-45': openFAQ === 3 }"
                  style="color: #00274D;"
                  fill="none" 
                  stroke="currentColor" 
                  viewBox="0 0 24 24"
                >
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4" />
                </svg>
              </button>
              <div v-if="openFAQ === 3" class="mt-4 text-sm md:text-base text-gray-700">
                <p>Yes. We use advanced encryption and strict confidentiality measures. Your information is never shared and is stored securely in compliance with industry standards.</p>
              </div>
            </div>
          </div>
        </div>

        <!-- Right Column: Illustration -->
        <div class="basis-[40%] p-[10px]">
          <img 
            src="/images/FAQ/FREQUENTLY-ASKED-QUESTIONS-1.png" 
            alt="FAQ illustration"
            class="w-full max-w-md h-auto object-contain"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'FAQSection',
  setup() {
    const openFAQ = ref<number | null>(null);

    const toggleFAQ = (index: number) => {
      openFAQ.value = openFAQ.value === index ? null : index;
    };

    return {
      openFAQ,
      toggleFAQ,
    };
  },
});
</script>

<style scoped>
</style>
