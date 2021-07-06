<template>
  <div id="__nuxt">
    <Hero />
    <Counter />
    <Subhero />
    <Testimonial />
    <Sponsors />
  </div>
</template>

<script>
import Hero from '~/components/index/Hero.vue'
import Counter from '~/components/index/Counter.vue'
import Subhero from '~/components/index/Subhero.vue'
import Testimonial from '~/components/index/Testimonial.vue'
import Sponsors from '~/components/index/Sponsors.vue'

export default {
  name: 'Landing',
  components: {
    Hero,
    Counter,
    Subhero,
    Testimonial,
    Sponsors,
  },
}
</script>
