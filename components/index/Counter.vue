<template>
  <section class="bg-yellow-400 skewed-top-right skew-top mr-for-radius">
    <div class="text-center py-24">
      <h2
        class="
          text-2xl
          tracking-tight
          leading-10
          font-extrabold
          text-gray-800
          sm:text-3xl sm:leading-none
          md:text-4xl
        "
      >
        Registration Starts On
        <br class="xl:hidden" />
        <span class="text-blue-700">July 30, 2021</span>
      </h2>
      <div class="my-10">
        <no-ssr>
          <flip-countdown deadline="2021-07-30 00:00:00"></flip-countdown>
        </no-ssr>
      </div>
      <p
        class="
          mt-3
          max-w-md
          mx-auto
          text-base text-gray-800
          sm:text-lg
          md:mt-5 md:text-xl md:max-w-3xl
          prose
          leading-normal
        "
      >
        The registration starts on July 30, 2021. The event will officialy start
        on August 15, 2021.
      </p>
    </div>
  </section>
</template>
<script>
import FlipCountdown from 'vue2-flip-countdown'

export default {
  components: { FlipCountdown },
}
</script>
<style>
.flip-card {
  font-family: var(--ff-primary);
}
span.flip-clock__slot {
  font-size: 2rem;
  color: black;
  font-family: var(--ff-primary);
}
</style>
