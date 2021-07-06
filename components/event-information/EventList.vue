<template>
  <section>
    <div class="py-20 bg-gray-50 radius-for-skewed">
      <div class="container mx-auto px-4">
        <div class="mb-16 flex flex-wrap items-center">
          <div class="w-full lg:w-1/2 text-center lg:text-left">
            <span class="text-blue-700 font-bold" data-config-id="caption"
              >Learn more about</span
            >
            <h2
              class="text-4xl lg:text-5xl text-gray-800 font-bold font-heading"
              data-config-id="header"
            >
              Our Challenges
            </h2>
          </div>
        </div>
        <div class="mb-8 flex flex-wrap rounded-lg shadow overflow-hidden">
          <div class="w-full lg:w-1/2 rounded-l">
            <img
              class="object-cover"
              src="https://images.unsplash.com/photo-1559827291-72ee739d0d9a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80"
              alt=""
              data-config-id="image1"
            />
          </div>
          <div class="w-full lg:w-1/2 py-6 lg:pt-10 px-6 rounded-r bg-white">
            <span class="text-sm text-gray-400" data-config-id="date1"
              >Sponsored by:
            </span>
            <h2 class="my-4 text-3xl text-red-700 font-bold">Bayanihan Swim</h2>
            <p class="mb-4 text-gray-400 leading-loose" data-config-id="desc1">
              Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
              dictum. Integer sit amet erat sit amet lectus lacinia mattis.
              Donec est tortor, fermentum at urna a, accumsan suscipit sem.
            </p>
          </div>
        </div>
        <div class="mb-8 flex flex-wrap rounded-lg shadow overflow-hidden">
          <div
            class="
              w-full
              lg:w-1/2
              py-6
              lg:pt-10
              px-6
              rounded-r
              bg-white
              order-1
              lg:order-0
            "
          >
            <span class="text-sm text-gray-400" data-config-id="date2"
              >Sponsored by:
            </span>
            <h2 class="my-4 text-3xl text-red-700 font-bold">Bayanihan Run</h2>
            <p class="mb-4 text-gray-400 leading-loose" data-config-id="desc2">
              Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
              dictum. Integer sit amet erat sit amet lectus lacinia mattis.
              Donec est tortor, fermentum at urna a, accumsan suscipit sem.
            </p>
          </div>
          <div class="w-full lg:w-1/2 rounded-l order-0 lg:order-1">
            <img
              class="object-cover"
              src="https://images.unsplash.com/photo-1559827291-72ee739d0d9a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80"
              alt=""
              data-config-id="image2"
            />
          </div>
        </div>
        <div class="mb-8 flex flex-wrap rounded-lg shadow overflow-hidden">
          <div class="w-full lg:w-1/2 rounded-l">
            <img
              class="object-cover"
              src="https://images.unsplash.com/photo-1559827291-72ee739d0d9a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80"
              alt=""
              data-config-id="image3"
            />
          </div>
          <div class="w-full lg:w-1/2 py-6 lg:pt-10 px-6 rounded-r bg-white">
            <span class="text-sm text-gray-400" data-config-id="date3"
              >Sponsored by:</span
            >
            <h2 class="my-4 text-3xl text-red-700 font-bold">Bayanihan Bike</h2>
            <p class="mb-4 text-gray-400 leading-loose" data-config-id="desc3">
              Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
              dictum. Integer sit amet erat sit amet lectus lacinia mattis.
              Donec est tortor, fermentum at urna a, accumsan suscipit sem.
            </p>
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
