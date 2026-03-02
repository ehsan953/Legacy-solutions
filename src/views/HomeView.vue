<template>
  <div class="home">
    <HeroSection />
    <UnclaimedFundsSection />
    <WhyPeopleChooseSection />
    <MoneyWaitingSection />
    <RecoveryProcessSection />
    <WhyChooseSection />
    <FAQSection />
    <YourMoneyWaitingSection />
    <StartRecoverySection />
    <CTASection />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HeroSection from '@/components/HeroSection.vue';
import UnclaimedFundsSection from '@/components/UnclaimedFundsSection.vue';
import MoneyWaitingSection from '@/components/MoneyWaitingSection.vue';
import RecoveryProcessSection from '@/components/RecoveryProcessSection.vue';
import WhyChooseSection from '@/components/WhyChooseSection.vue';
import YourMoneyWaitingSection from '@/components/YourMoneyWaitingSection.vue';
import StartRecoverySection from '@/components/StartRecoverySection.vue';
import WhyPeopleChooseSection from '@/components/WhyPeopleChooseSection.vue';
import FAQSection from '@/components/FAQSection.vue';
import CTASection from '@/components/CTASection.vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    HeroSection,
    UnclaimedFundsSection,
    MoneyWaitingSection,
    RecoveryProcessSection,
    WhyChooseSection,
    YourMoneyWaitingSection,
    StartRecoverySection,
    WhyPeopleChooseSection,
    FAQSection,
    CTASection
  },
});
</script>
