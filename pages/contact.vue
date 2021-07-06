<template>
  <div id="__nuxt">
    <section class="pt-20 bg-gray-50">
      <div class="py-20 bg-gray-50 radius-for-skewed">
        <div class="container mx-auto px-4">
          <div class="mb-12">
            <h2
              class="text-4xl lg:text-5xl font-bold font-heading"
              data-config-id="header"
            >
              Contact
            </h2>
            <p class="text-gray-500 leading-loose" data-config-id="desc">
              Got any questions? Let&rsquo;s talk about it.
            </p>
          </div>
          <div class="flex flex-wrap">
            <div class="w-full lg:w-1/2 mb-16 lg:mb-0">
              <div class="flex flex-wrap">
                <div class="mb-12 w-full md:w-1/2 lg:w-1/2">
                  <h3
                    class="mb-2 text-3xl lg:text-4xl font-bold"
                    data-config-id="contact1"
                  >
                    Office
                  </h3>
                  <p class="text-gray-400" data-config-id="contact1-val">
                    #12 Blk 1 Lot 12 Jose St.
                  </p>
                  <p class="text-gray-400" data-config-id="contact1-val2">
                    1632 Manila, Philippines
                  </p>
                </div>
                <div class="mb-12 w-full md:w-1/2">
                  <h3
                    class="mb-2 text-3xl lg:text-4xl font-bold"
                    data-config-id="contact2"
                  >
                    Contacts
                  </h3>
                  <p class="text-gray-400" data-config-id="contact2-val">
                    info@bayanihanchallenge.com
                  </p>
                </div>
                <div class="w-full md:w-1/3 lg:w-full">
                  <h3
                    class="mb-2 text-3xl lg:text-4xl font-bold"
                    data-config-id="contact3"
                  >
                    Socials
                  </h3>
                  <div class="flex">
                    <a class="mr-3" href="#">
                      <img
                        src="atis-assets/social/facebook-purple.svg"
                        alt=""
                      />
                    </a>
                    <a class="mr-3" href="#">
                      <img src="atis-assets/social/twitter-purple.svg" alt="" />
                    </a>
                    <a href="#">
                      <img
                        src="atis-assets/social/instagram-purple.svg"
                        alt=""
                      />
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <div class="w-full lg:w-1/2">
              <div class="max-w-md lg:mx-auto">
                <form action="">
                  <div class="mb-4">
                    <input
                      class="
                        w-full
                        p-4
                        text-xs
                        font-semibold
                        leading-none
                        bg-white
                        rounded
                        outline-none
                      "
                      type="text"
                      placeholder="Subject"
                    />
                  </div>
                  <div class="mb-4">
                    <input
                      class="
                        w-full
                        p-4
                        text-xs
                        font-semibold
                        leading-none
                        bg-white
                        rounded
                        outline-none
                      "
                      type="text"
                      placeholder="Name"
                    />
                  </div>
                  <div class="mb-4">
                    <input
                      class="
                        w-full
                        p-4
                        text-xs
                        font-semibold
                        leading-none
                        bg-white
                        rounded
                        outline-none
                      "
                      type="email"
                      placeholder="name@example.com"
                    />
                  </div>
                  <div class="mb-4">
                    <textarea
                      class="
                        w-full
                        h-24
                        p-4
                        text-xs
                        font-semibold
                        leading-none
                        resize-none
                        bg-white
                        rounded
                        outline-none
                        text-gray-800
                      "
                      type="text"
                      placeholder="Message..."
                    ></textarea>
                  </div>
                  <div class="flex justify-between items-center">
                    <label>
                      <input
                        class="mr-1"
                        type="checkbox"
                        name="terms"
                        value="1"
                      />
                      <span class="text-sm font-semibold" data-config-id="terms"
                        >I agree to terms and conditions.</span
                      >
                    </label>
                    <button
                      class="
                        inline-block
                        py-2
                        px-6
                        rounded-l-xl rounded-t-xl
                        bg-blue-700
                        hover:bg-blue-800
                        text-gray-50
                        font-bold
                        leading-loose
                        transition
                        duration-200
                      "
                      data-config-id="primary-action"
                    >
                      Submit
                    </button>
                  </div>
                </form>
              </div>
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
  </div>
</template>

<script>
export default {
  name: 'Landing',
}
</script>
