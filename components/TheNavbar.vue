<template>
  <section>
    <nav
      :class="headerClassList"
      class="
        fixed
        w-screen
        px-6
        2xl:px-20
        py-6
        flex
        justify-between
        items-center
        bg-transparent
        z-50
      "
    >
      <a
        class="text-3xl font-bold leading-none"
        href="#"
        data-config-id="brand"
      >
        <Logo />
      </a>
      <div class="2xl:hidden">
        <button
          class="navbar-burger flex items-center text-red-600 p-3"
          @click.prevent.stop="openBurger"
        >
          <svg
            class="block h-4 w-4 fill-current"
            viewbox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <title>Mobile menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
          </svg>
        </button>
      </div>
      <ul
        class="
          hidden
          absolute
          top-1/2
          left-1/2
          transform
          -translate-y-1/2 -translate-x-1/2
          2xl:flex
          2xl:mx-auto
          2xl:flex
          2xl:items-center
          2xl:w-auto
          2xl:space-x-6
        "
      >
        <li>
          <NuxtLink class="text-sm text-gray-400 hover:text-gray-500" to="/"
            >Home</NuxtLink
          >
        </li>
        <li class="text-gray-300">
          <svg
            class="w-4 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewbox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <NuxtLink
            class="text-sm text-gray-400 hover:text-gray-500"
            to="/event-information"
            >Event Information</NuxtLink
          >
        </li>
        <li class="text-gray-300">
          <svg
            class="w-4 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewbox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <NuxtLink
            class="text-sm text-gray-400 hover:text-gray-500"
            to="/leaderboards"
            >Leaderboards</NuxtLink
          >
        </li>
        <li class="text-gray-300">
          <svg
            class="w-4 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewbox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <NuxtLink class="text-sm text-gray-400 hover:text-gray-500" to="/faq"
            >FAQ</NuxtLink
          >
        </li>
        <li class="text-gray-300">
          <svg
            class="w-4 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewbox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <NuxtLink
            class="text-sm text-gray-400 hover:text-gray-500"
            to="/contact"
            >Contact</NuxtLink
          >
        </li>
      </ul>
      <NuxtLink
        class="
          hidden
          2xl:inline-block 2xl:ml-auto 2xl:mr-3
          py-2
          px-6
          bg-gray-200
          hover:bg-gray-300
          text-sm text-gray-900
          font-bold
          rounded-l-xl rounded-t-xl
          transition
          duration-200
        "
        to="/submit"
        data-config-id="secondary-action"
        >Submit Activity</NuxtLink
      ><NuxtLink
        class="
          hidden
          2xl:inline-block
          py-2
          px-6
          bg-red-500
          hover:bg-red-600
          text-sm text-white
          font-bold
          rounded-l-xl rounded-t-xl
          transition
          duration-200
        "
        to="/register"
        data-config-id="primary-action"
        >Register</NuxtLink
      >
    </nav>

    <!-- Sidebar -->

    <div v-if="isOpen" class="navbar-menu relative z-50">
      <div
        class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"
        @click="closeBurger"
      ></div>
      <nav
        class="
          fixed
          top-0
          left-0
          bottom-0
          flex flex-col
          w-5/6
          max-w-sm
          py-6
          px-6
          bg-white
          border-r
          overflow-y-auto
        "
      >
        <div class="flex items-center mb-8">
          <Logo />
          <button class="navbar-close" @click="closeBurger">
            <svg
              class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewbox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M6 18L18 6M6 6l12 12"
              ></path>
            </svg>
          </button>
        </div>
        <div>
          <ul>
            <li class="mb-1">
              <NuxtLink
                class="
                  block
                  p-4
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-red-50 hover:text-red-600
                  rounded
                "
                to="/"
                >Home</NuxtLink
              >
            </li>
            <li class="mb-1">
              <NuxtLink
                class="
                  block
                  p-4
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-red-50 hover:text-red-600
                  rounded
                "
                to="/event-information"
                >Event Information</NuxtLink
              >
            </li>
            <li class="mb-1">
              <NuxtLink
                class="
                  block
                  p-4
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-red-50 hover:text-red-600
                  rounded
                "
                to="/leaderboards"
                >Leaderboards</NuxtLink
              >
            </li>
            <li class="mb-1">
              <NuxtLink
                class="
                  block
                  p-4
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-red-50 hover:text-red-600
                  rounded
                "
                to="/faq"
                >FAQ</NuxtLink
              >
            </li>
            <li class="mb-1">
              <NuxtLink
                class="
                  block
                  p-4
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-red-50 hover:text-red-600
                  rounded
                "
                to="/contact"
                >Contact</NuxtLink
              >
            </li>
          </ul>
        </div>
        <div class="mt-auto">
          <div class="pt-6">
            <NuxtLink
              class="
                block
                px-4
                py-3
                mb-3
                leading-loose
                text-xs text-center
                font-semibold
                leading-none
                bg-gray-300
                hover:bg-gray-400
                rounded-l-xl rounded-t-xl
              "
              to="/submit"
              >Submit Activity</NuxtLink
            ><NuxtLink
              class="
                block
                px-4
                py-3
                mb-2
                leading-loose
                text-xs text-center text-white
                font-semibold
                bg-red-600
                hover:bg-red-700
                rounded-l-xl rounded-t-xl
              "
              to="/register"
              >Register</NuxtLink
            >
          </div>
          <p class="my-4 text-xs text-center text-gray-400">
            <span data-config-id="copy">&copy; 2020 All rights reserved.</span>
          </p>
          <div class="text-center">
            <a class="inline-block px-1" href="#">
              <img src="atis-assets/social/facebook.svg" alt="" />
            </a>
            <a class="inline-block px-1" href="#">
              <img src="atis-assets/social/twitter.svg" alt="" />
            </a>
            <a class="inline-block px-1" href="#">
              <img src="atis-assets/social/instagram.svg" alt="" />
            </a>
          </div>
        </div>
      </nav>
    </div>
  </section>
</template>

<script>
import Logo from '@/components/Logo'

export default {
  name: 'TheHeader',
  components: {
    logo: Logo,
  },
  data() {
    return {
      scrollY: 0,
      isOpen: false,
    }
  },
  computed: {
    isSticky() {
      return this.scrollY > 10
    },
    headerClassList() {
      return this.isSticky ? 'bg-white shadow' : ''
    },
  },
  mounted() {
    this.scrollY = window.scrollY
    document.addEventListener('click', this.onClick)
    document.addEventListener('scroll', this.onScroll)
  },
  beforeDestroy() {
    document.removeEventListener('click', this.onClick, true)
    document.removeEventListener('scroll', this.onScroll, true)
  },
  methods: {
    onScroll() {
      this.scrollY = window.scrollY
    },
    openBurger() {
      this.isOpen = true
    },
    closeBurger() {
      this.isOpen = false
    },
  },
}
</script>

<style scoped>
/* exact link will show the primary color for only the exact matching link */
a.nuxt-link-exact-active {
  font-weight: bold;
  color: #b91c1c;
}
</style>
