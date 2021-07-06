<template>
  <div id="__nuxt">
    <section class="py-10 bg-gray-50">
      <div class="container mx-auto px-4">
        <div class="max-w-xl mx-auto mt-20">
          <div class="p-6 lg:p-12 mb-6 bg-white shadow rounded">
            <div class="mb-6">
              <span class="text-blue-700">Bayanihan Challenge</span>
              <h3 class="text-4xl font-bold">Submit Activity</h3>
            </div>
            <form action="">
              <div class="flex flex-wrap px-2 mb-3">
                <div class="mb-3 w-full lg:w-1/2 px-2">
                  <label
                    class="block text-gray-700 text-sm font-bold mb-2"
                    for=""
                    data-config-id="02_label"
                    >Bib #</label
                  >
                  <input
                    class="
                      appearance-none
                      block
                      w-full
                      py-3
                      px-4
                      leading-tight
                      text-gray-700
                      bg-gray-50
                      focus:bg-white
                      border border-gray-200
                      focus:border-gray-500
                      rounded
                      focus:outline-none
                    "
                    type="text"
                    name="field-name"
                    placeholder="001"
                  />
                </div>
                <div class="mb-3 w-full lg:w-1/2 px-2">
                  <label
                    class="block text-gray-700 text-sm font-bold mb-2"
                    for=""
                    data-config-id="02_label"
                    >Account Pin</label
                  >
                  <input
                    class="
                      appearance-none
                      block
                      w-full
                      py-3
                      px-4
                      leading-tight
                      text-gray-700
                      bg-gray-50
                      focus:bg-white
                      border border-gray-200
                      focus:border-gray-500
                      rounded
                      focus:outline-none
                    "
                    type="text"
                    name="field-name"
                    placeholder="####"
                  />
                </div>
              </div>
              <div class="mb-3 px-4">
                <label class="block text-gray-700 text-sm font-bold mb-2" for=""
                  >Email</label
                >
                <input
                  class="
                    appearance-none
                    block
                    w-full
                    py-3
                    px-4
                    leading-tight
                    text-gray-700
                    bg-gray-50
                    focus:bg-white
                    border border-gray-200
                    focus:border-gray-500
                    rounded
                    focus:outline-none
                  "
                  type="email"
                  name="email"
                  placeholder="name@website.com"
                />
              </div>
              <div class="mb-3 flex flex-col px-4">
                <label
                  class="block text-gray-700 text-sm font-bold"
                  for=""
                  data-config-id="04_label"
                  >Activity</label
                >
                <div class="relative">
                  <select
                    class="
                      appearance-none
                      block
                      w-full
                      py-3
                      px-4
                      leading-tight
                      text-gray-700
                      bg-gray-50
                      focus:bg-white
                      border border-gray-200
                      focus:border-gray-500
                      rounded
                      focus:outline-none
                    "
                    name="field-name"
                    data-config-id="04_select"
                  >
                    <option data-config-id="04_opt1">Swim</option>
                    <option data-config-id="04_opt2">Bike</option>
                    <option data-config-id="04_opt3">Run</option>
                  </select>
                  <div
                    class="
                      pointer-events-none
                      absolute
                      inset-y-0
                      right-0
                      flex
                      items-center
                      px-2
                      text-gray-700
                    "
                  >
                    <svg
                      class="fill-current h-4 w-4"
                      xmlns="http://www.w3.org/2000/svg"
                      viewbox="0 0 20 20"
                    >
                      <path
                        d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
                      ></path>
                    </svg>
                  </div>
                </div>
              </div>
              <div class="flex flex-wrap p-2 mb-3">
                <div class="mb-3 w-full lg:w-1/2 px-2">
                  <label
                    class="block text-gray-700 text-sm font-bold mb-2"
                    for=""
                    >Distance in km</label
                  >
                  <input
                    class="
                      appearance-none
                      block
                      w-full
                      py-3
                      px-4
                      leading-tight
                      text-gray-700
                      bg-gray-50
                      focus:bg-white
                      border border-gray-200
                      focus:border-gray-500
                      rounded
                      focus:outline-none
                    "
                    type="text"
                    name="field-name"
                    placeholder="10.0"
                  />
                </div>
                <div class="mb-3 w-full lg:w-1/2 px-2">
                  <label
                    class="block text-gray-700 text-sm font-bold mb-2"
                    for=""
                    >Time</label
                  >
                  <input
                    class="
                      appearance-none
                      block
                      w-full
                      py-3
                      px-4
                      leading-tight
                      text-gray-700
                      bg-gray-50
                      focus:bg-white
                      border border-gray-200
                      focus:border-gray-500
                      rounded
                      focus:outline-none
                    "
                    type="text"
                    name="field-name"
                    placeholder="hh:mm:ss"
                  />
                </div>
              </div>
              <div class="mb-6">
                <label class="flex px-5 bg-white rounded">
                  <input
                    type="file"
                    placeholder="Choose file.."
                    name="Choose file"
                  />
                </label>
              </div>
              <div class="text-center">
                <button
                  class="
                    mb-2
                    w-full
                    py-4
                    bg-blue-700
                    hover:bg-blue-800
                    rounded
                    text-sm
                    font-bold
                    text-gray-50
                    transition
                    duration-200
                  "
                >
                  Submit Activity
                </button>
              </div>
            </form>
          </div>
          <p class="text-xs text-center text-gray-400" data-config-id="terms">
            <a class="underline hover:text-gray-500" href="#">Policy privacy</a>
            and
            <a class="underline hover:text-gray-500" href="#">Terms of Use</a>
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Landing',
}
</script>
