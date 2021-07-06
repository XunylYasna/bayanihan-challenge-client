<template>
  <div id="__nuxt">
    <Hero />
    <HowTo />
    <EventList />
    <FaqLink />
  </div>
</template>

<script>
import Hero from '~/components/event-information/Hero.vue'
import HowTo from '~/components/event-information/HowTo.vue'
import EventList from '~/components/event-information/EventList.vue'
import FaqLink from '~/components/event-information/FaqLink.vue'

export default {
  name: 'Landing',
  components: {
    Hero,
    HowTo,
    EventList,
    FaqLink,
  },
}
</script>
