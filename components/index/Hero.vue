<template>
  <section class="skewed-bottom-right bg-yellow-400">
    <div class="bg-gray-50 pt-12 py-12 2xl:pt-16 2xl:pb-40 radius-for-skewed">
      <div class="container mx-auto px-5 lg:px-20 pt-40">
        <div class="flex flex-wrap">
          <div
            class="
              w-full
              lg:w-1/2
              px-4
              mb-12
              md:mb-20
              lg:mb-0
              flex
              items-center
            "
          >
            <div class="w-full text-center lg:text-left lg:ml-10">
              <div class="max-w-md mx-auto lg:mx-0">
                <h2
                  class="
                    mb-3
                    text-4xl
                    lg:text-5xl
                    text-gray-800
                    font-bold font-heading
                  "
                >
                  <span>Primary event</span>
                  <span class="text-blue-700">tagline</span>
                </h2>
              </div>
              <div class="max-w-sm mx-auto lg:mx-0">
                <p class="mb-6 text-gray-400 leading-loose">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Pellentesque efficitur nisl sodales egestas lobortis.
                </p>
                <div>
                  <NuxtLink
                    class="
                      inline-block
                      mb-3
                      lg:mb-0 lg:mr-3
                      w-full
                      lg:w-auto
                      py-2
                      px-6
                      leading-loose
                      bg-blue-700
                      hover:bg-blue-700
                      text-white
                      font-semibold
                      rounded-l-xl rounded-t-xl
                      transition
                      duration-200
                    "
                    to="/register"
                    >Register Now!</NuxtLink
                  ><NuxtLink
                    class="
                      inline-block
                      w-full
                      lg:w-auto
                      py-2
                      px-6
                      leading-loose
                      font-semibold
                      bg-gray-400
                      hover:bg-gray-500
                      rounded-l-xl rounded-t-xl
                      transition
                      duration-200
                    "
                    to="/event-information"
                    >Learn More</NuxtLink
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="w-full lg:w-1/2 px-4 flex items-center justify-center">
            <div class="relative" style="z-index: 0">
              <img
                class="
                  h-128
                  w-full
                  max-w-lg
                  object-cover
                  rounded-3xl
                  md:rounded-br-none
                "
                src="https://images.unsplash.com/photo-1462826303086-329426d1aef5?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80"
                alt=""
              />
              <img
                class="hidden md:block absolute"
                style="top: -2rem; right: 3rem; z-index: -1"
                src="atis-assets/elements/blue-up.svg"
                alt=""
              />
              <img
                class="hidden md:block absolute"
                style="bottom: -2rem; right: -2rem; z-index: -1"
                src="atis-assets/elements/wing-purple-down.svg"
                alt=""
              />
              <img
                class="hidden md:block absolute"
                style="top: 3rem; right: -3rem; z-index: -1"
                src="atis-assets/elements/bullets-yellow-right.svg"
                alt=""
              />
              <img
                class="hidden md:block absolute"
                style="bottom: 2.5rem; left: -4.5rem; z-index: -1"
                src="atis-assets/elements/bullets-pink-left.svg"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
