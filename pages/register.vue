<template>
  <div id="__nuxt">
    <section class="py-10 bg-gray-50">
      <div class="container mx-auto px-4">
        <div class="max-w-xl mx-auto mt-20">
          <div class="p-6 lg:p-12 mb-6 bg-white shadow rounded">
            <div class="mb-6">
              <span class="text-blue-700">Bayanihan Challenge</span>
              <h3 class="text-4xl font-bold">Register</h3>
            </div>
            <form action="">
              <div class="flex flex-wrap px-2 mb-3">
                <div class="mb-3 w-full lg:w-1/2 px-2">
                  <label
                    class="block text-gray-700 text-sm font-bold mb-2"
                    for=""
                    data-config-id="02_label"
                    >First Name</label
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
                    placeholder="John"
                  />
                </div>
                <div class="mb-3 w-full lg:w-1/2 px-2">
                  <label
                    class="block text-gray-700 text-sm font-bold mb-2"
                    for=""
                    data-config-id="02_label"
                    >Last Name</label
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
                    placeholder="Aguinaldo"
                  />
                </div>
              </div>
              <div class="mb-6 px-4">
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
              <div class="mb-6 flex flex-col px-4">
                <label class="block text-gray-700 text-sm font-bold mb-2" for=""
                  >Challenges</label
                >
                <label for="">
                  <input
                    class="ml-2"
                    type="checkbox"
                    name="field-name"
                    value="example value"
                    checked=""
                    data-config-id="05_checkbox"
                  />
                  <span class="ml-1" data-config-id="05_label">Swim</span>
                </label>
                <label for="">
                  <input
                    class="ml-2"
                    type="checkbox"
                    name="field-name"
                    value="example value"
                    checked=""
                    data-config-id="05_checkbox"
                  />
                  <span class="ml-1" data-config-id="05_label">Run</span>
                </label>
                <label for="">
                  <input
                    class="ml-2"
                    type="checkbox"
                    name="field-name"
                    value="example value"
                    checked=""
                    data-config-id="05_checkbox"
                  />
                  <span class="ml-1" data-config-id="05_label">Bike</span>
                </label>
              </div>
              <div class="mb-6 px-4">
                <label class="block text-gray-700 text-sm font-bold mb-2" for=""
                  >Address</label
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
                  name="address1"
                  placeholder="#1 Malakas St. Baranggay 3"
                />
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
                    mt-1
                  "
                  type="text"
                  name="address2"
                  placeholder="1630 Manila City, Philippines"
                />
              </div>
              <div class="mb-6 px-4">
                <label class="block text-gray-700 text-sm font-bold mb-2" for=""
                  >Payment Method</label
                >
                <div class="mb-1">
                  <label for="">
                    <input
                      type="radio"
                      name="radio-name"
                      value="option 1"
                      checked=""
                    />
                    <span class="ml-1" data-config-id="06_label1">GCash</span>
                  </label>
                </div>
                <div>
                  <label for="">
                    <input type="radio" name="radio-name" value="option 2" />
                    <span class="ml-1" data-config-id="06_label2">Paypal</span>
                  </label>
                </div>
                <div>
                  <label for="">
                    <input type="radio" name="radio-name" value="option 2" />
                    <span class="ml-1" data-config-id="06_label2"
                      >Bank Transfer</span
                    >
                  </label>
                </div>
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
                  Register
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
