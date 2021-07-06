<template>
  <div class="leading-normal tracking-normal text-white gradient">
    <TheNavbar />
    <nuxt />
    <TheFooter />
  </div>
</template>

<script>
import TheNavbar from '~/components/TheNavbar.vue'
import TheFooter from '~/components/TheFooter.vue'

export default {
  components: {
    TheNavbar,
    TheFooter,
  },
  head() {
    return {
      title: 'Bayanihan Challenge',
      meta: [
        { charset: 'utf-8' },
        { name: 'viewport', content: 'width=device-width, initial-scale=1' },
        {
          hid: 'description',
          name: 'description',
          content: 'Take part in the Bayanihan Virtual Challenge',
        },
        {
          name: 'keywords',
          content:
            'Virtual Run, Races to join, Online Running Event, Bayanihan  Virtual Challenge, Fitness Philippines',
        },
      ],
      // link: [{ rel: 'icon', type: 'image/x-icon', href: '/gumamela.png' }],
    }
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=K2D:wght@400;700&family=Lato&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Mulish:wght@700&display=swap');
:root {
  --ff-primary: 'K2D', sans-serif;
  --ff-secondary: 'Lato', sans-serif;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: var(--ff-primary);
  --tw-text-opacity: 1;
  color: rgba(31, 41, 55, var(--tw-text-opacity));
}
p {
  font-family: var(--ff-secondary);
  --tw-text-opacity: 1;
  color: rgba(31, 41, 55, var(--tw-text-opacity));
}
input {
  --tw-text-opacity: 1;
  color: rgba(31, 41, 55, var(--tw-text-opacity));
}
label {
  --tw-text-opacity: 1;
  color: rgba(31, 41, 55, var(--tw-text-opacity));
}

.skew {
  display: none;
}

.skewed-top-right .skew-top.mr-for-radius {
  display: block;
}

.skewed-top-left .skew-top.ml-for-radius {
  display: block;
}

.skewed-bottom-right .skew-bottom.mr-for-radius {
  display: block;
}

.skewed-bottom-left .skew-bottom.ml-for-radius {
  display: block;
}

.skewed-top-right .radius-for-skewed {
  border-top-right-radius: 6rem;
}

.skewed-top-left .radius-for-skewed {
  border-top-left-radius: 6rem;
}

.skewed-bottom-right .radius-for-skewed {
  border-bottom-right-radius: 6rem;
}

.skewed-bottom-left .radius-for-skewed {
  border-bottom-left-radius: 6rem;
}

.border-radius-custom {
  border-radius: 6rem;
}
</style>
