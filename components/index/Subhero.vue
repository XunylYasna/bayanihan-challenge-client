<template>
  <section class="bg-yellow-400">
    <div
      class="bg-gray-50 skewed-top-left radius-for-skewed border-radius-custom"
    >
      <div class="py-20 bg-white radius-for-skewed">
        <div class="container mx-auto px-4">
          <div class="mb-16 max-w-md mx-auto text-center">
            <span class="text-blue-700 font-bold"
              >Dolor sit amet consectutar</span
            >
            <h2
              class="text-4xl lg:text-5xl font-bold font-heading text-gray-800"
            >
              Join us in these event categories
            </h2>
          </div>
          <div class="flex flex-wrap -mx-4">
            <div class="mb-8 lg:mb-0 w-full lg:w-1/3 px-4">
              <div class="py-12 px-6 bg-white rounded shadow text-center">
                <span class="mb-6 inline-block p-2 rounded-lg bg-yellow-100">
                  <svg
                    class="w-10 h-10 text-yellow-500"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewbox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"
                    ></path>
                  </svg>
                </span>
                <h3
                  class="
                    px-8
                    mb-4
                    text-2xl
                    font-bold font-heading
                    text-gray-800
                  "
                >
                  Swim
                </h3>
                <p class="text-gray-500">
                  Donec ut ligula nunc. Mauris blandit vel est et facilisis.
                  Integer sapien felis.
                </p>
              </div>
            </div>
            <div class="mb-8 lg:mb-0 w-full lg:w-1/3 px-4">
              <div class="py-12 px-6 bg-white rounded shadow text-center">
                <span class="mb-6 inline-block p-2 rounded-lg bg-purple-100">
                  <svg
                    class="w-10 h-10 text-purple-500"
                    xmlns="http://www.w3.org/2000/svg"
                    viewbox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"
                    ></path>
                  </svg>
                </span>
                <h3
                  class="
                    px-8
                    mb-4
                    text-2xl
                    font-bold font-heading
                    text-gray-800
                  "
                >
                  Bike
                </h3>
                <p class="text-gray-500">
                  Ut tempus tellus ac nisi vestibulum tempus. Nunc tincidunt
                  lectus libero.
                </p>
              </div>
            </div>
            <div class="w-full lg:w-1/3 px-4">
              <div class="py-12 px-6 bg-white rounded shadow text-center">
                <span class="mb-6 inline-block p-2 rounded bg-pink-100">
                  <svg
                    class="w-10 h-10 text-pink-500"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewbox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M16 4v12l-4-2-4 2V4M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"
                    ></path>
                  </svg>
                </span>
                <h3
                  class="
                    px-8
                    mb-4
                    text-2xl
                    font-bold font-heading
                    text-gray-800
                  "
                >
                  Run
                </h3>
                <p class="text-gray-500">
                  Donec ut ligula nunc. Mauris blandit vel est et facilisis.
                  Integer sapien felis.
                </p>
              </div>
            </div>
          </div>
        </div>

        <div class="flex">
          <NuxtLink
            class="
              inline-block
              py-2
              px-6
              mx-auto
              mt-7
              leading-loose
              bg-blue-700
              hover:bg-blue-800
              text-white
              font-semibold
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
  </section>
</template>
