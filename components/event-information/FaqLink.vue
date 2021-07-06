<template>
  <section class="py-20 bg-white">
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap items-center justify-center">
        <div
          class="
            w-full
            lg:w-auto
            mb-10
            lg:mb-0
            text-gray-800 text-center
            lg:text-left
          "
        >
          <h2
            class="
              max-w-xl
              mx-auto
              lg:mx-0
              mb-2
              text-4xl
              lg:text-5xl
              font-bold font-heading
            "
            data-config-id="header"
          >
            Register now or contact us for more information.
          </h2>
          <p
            class="max-w-xl mx-auto lg:mx-0 text-gray-500 leading-loose"
            data-config-id="desc"
          >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Pellentesque efficitur nisl sodales egestas lobortis.
          </p>
        </div>
        <div class="w-full lg:w-auto lg:ml-auto text-center">
          <NuxtLink
            class="
              inline-block
              py-2
              px-6
              bg-blue-700
              hover:bg-blue-800
              text-white
              font-bold
              leading-loose
              rounded-l-xl rounded-t-xl
              transition
              duration-200
              mr-2
            "
            to="/contact"
            >Contact Us</NuxtLink
          >
          <NuxtLink
            class="
              inline-block
              py-2
              px-6
              bg-blue-700
              hover:bg-blue-800
              text-white
              font-bold
              leading-loose
              rounded-l-xl rounded-t-xl
              transition
              duration-200
            "
            to="/register"
            >Register</NuxtLink
          >
        </div>
      </div>
    </div>
  </section>
</template>
