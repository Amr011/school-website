<script>
import navBar from '@/components/mainNavbar.vue'
import Hero from '@/components/hero.vue'
import AboutTop from '@/components/about-top.vue'
import Features from '@/components/features.vue'
import AboutMid from '@/components/about-mid.vue'
import License from '@/components/license.vue'
import Faq from '@/components/faq.vue'
import CallToAction from '@/components/call-to-action.vue'
import Contact from '@/components/contact.vue'
import mainFooter from '@/components/mainFooter.vue'
export default {
  components: {
    navBar,
    Hero,
    AboutTop,
    Features,
    AboutMid,
    License,
    Faq,
    CallToAction,
    Contact,
    mainFooter,
  },
}
</script>

<template>
  <div>
    <div class="px-8 md:px-4 lg:px-0 xl:px-0">
      <nav-bar />
      <hero />
      <about-top />
      <features />
      <about-mid />
      <license />
      <faq />
      <call-to-action />
      <contact />
      <hr />
      <main-footer />
    </div>
  </div>
</template>

<style></style>
