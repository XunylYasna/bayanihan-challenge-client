<template>
  <section class="bg-red-700">
    <div class="py-20 bg-red-700 radius-for-skewed">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap mb-6 lg:mb-20">
          <div class="mb-6 w-full lg:w-1/5">
            <a
              class="text-3xl font-bold leading-none"
              href="#"
              data-config-id="brand"
            >
              <Logo />
            </a>
          </div>
          <div class="mb-5 w-full lg:w-1/5">
            <p class="text-white leading-loose" data-config-id="desc">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
              luctus eget justo.
            </p>
          </div>
          <div class="w-full lg:w-3/5 flex flex-wrap -mx-3 justify-end">
            <div class="mb-6 w-full md:w-1/2 lg:w-1/4 lg:mr-6 px-3">
              <h5 class="mb-4 font-bold" data-config-id="header1">Office</h5>
              <p class="text-white leading-loose" data-config-id="contact1">
                359 Hidden Valley Road, NY
              </p>
            </div>
            <div class="mb-6 w-full md:w-1/2 lg:w-1/4 px-3">
              <h5 class="mb-4 font-bold" data-config-id="header2">Contacts</h5>
              <p class="text-white" data-config-id="contact2">
                info@bayanihanchallenge.com
              </p>
            </div>
          </div>
        </div>
        <div class="w-full flex justify-between">
          <p class="text-sm text-white" data-config-id="copy">
            &copy; 2021. All rights reserved.
          </p>
          <div class="flex space-x-2 lg:space-x-4">
            <a href="#">
              <img src="atis-assets/social/facebook-purple.svg" alt="" />
            </a>
            <a href="#">
              <img src="atis-assets/social/twitter-purple.svg" alt="" />
            </a>
            <a href="#">
              <img src="atis-assets/social/instagram-purple.svg" alt="" />
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="skew skew-bottom mr-for-radius">
      <svg
        class="h-8 md:h-12 lg:h-20 w-full text-gray-50"
        viewbox="0 0 10 10"
        preserveaspectratio="none"
      >
        <polygon fill="currentColor" points="0 0 10 0 0 10"></polygon>
      </svg>
    </div>
    <div class="skew skew-bottom ml-for-radius">
      <svg
        class="h-8 md:h-12 lg:h-20 w-full text-gray-50"
        viewbox="0 0 10 10"
        preserveaspectratio="none"
      >
        <polygon fill="currentColor" points="0 0 10 0 10 10"></polygon>
      </svg>
    </div>
  </section>
</template>

<script>
import Logo from '@/components/Logo'

export default {
  name: 'TheFooter',
  components: {
    logo: Logo,
  },
}
</script>
