<template>
  <div class="home">
    <HeroSection />
    <UnclaimedFundsSection />
    <WhyPeopleChooseSection />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HeroSection from '@/components/HeroSection.vue';
import UnclaimedFundsSection from '@/components/UnclaimedFundsSection.vue';
import WhyPeopleChooseSection from '@/components/WhyPeopleChooseSection.vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    HeroSection,
    UnclaimedFundsSection,
    WhyPeopleChooseSection,
  },
});
</script>
