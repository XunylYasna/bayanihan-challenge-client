<template>
  <div id="__nuxt">
    <Leaderboards />
  </div>
</template>

<script>
import Leaderboards from '~/components/leaderboards/Leaderboards.vue'

export default {
  name: 'Landing',
  components: {
    Leaderboards,
  },
}
</script>
