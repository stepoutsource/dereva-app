<template>
  <div class="is-boxed has-animations">
    <div class="body-wrap boxed-container">
      <site-header></site-header>
      <main>
        <hero-section/>
        <features-section />
        <testimonials-section/>
      </main>
      <site-footer></site-footer>
    </div>
  </div>
</template>

<script>

import SiteHeader from "@/components/site-header.vue";
import HeroSection from "@/components/hero-section.vue";
import FeaturesSection from "@/components/features-section.vue";
import TestimonialsSection from "@/components/testimonials-section.vue";
import SiteFooter from "@/components/site-footer.vue";

export default {
  name: 'HomeView',
  components: {
    SiteFooter,
    TestimonialsSection,
    FeaturesSection,
    HeroSection,
    SiteHeader,
  }
}
</script>
