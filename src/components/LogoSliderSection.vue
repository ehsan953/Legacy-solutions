<template>
  <section class="bg-white py-6 md:py-[60px] border-t border-gray-200">
    <div class="container max-w-7xl mx-auto flex flex-col gap-5">
      <hr class="py-5">
      <div class="flex flex-wrap items-center justify-center gap-8 md:gap-12">
        <img
          src="/images/logos/turbologo.webp"
          alt="Turbologo"
          class="h-8 md:h-10 w-auto object-contain"
        />
        <img
          src="/images/logos/mondi-logo.webp"
          alt="Mondi"
          class="h-8 md:h-10 w-auto object-contain"
        />
        <img
          src="/images/logos/logotype-logo.webp"
          alt="Logotype"
          class="h-8 md:h-10 w-auto object-contain"
        />
        <img
          src="/images/logos/maxton-design.webp"
          alt="Maxton Design"
          class="h-8 md:h-10 w-auto object-contain"
        />
        <img
          src="/images/logos/duragas.webp"
          alt="Duragas"
          class="h-8 md:h-10 w-auto object-contain"
        />
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'LogoSliderSection',
});
</script>

<style scoped>
</style>

