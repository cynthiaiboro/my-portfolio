<template>
  <div class="relative overflow-hidden bg-cream">
    <footer id="footer" class="relative z-50 pt-24 max-w-7xl mx-auto container">
      <div>
        <div class="mx-auto container">
          <div class="lg:flex">
            <div class="w-full lg:w-5/12 mb-16 lg:mb-0">
              <div class="w-full px-6">
                <nuxt-link to="/" class="flex mb-4">
                  <img class="h-2 md:w-auto sm:h-5 my-auto" src="/Logo.svg" />
                  <span class="text-3xl font-bold pb-3 text-darktitle pl-3">
                    ExpressWeb JS
                  </span>
                </nuxt-link>

                <p class="text-xs">A NodeJs Framework for you</p>
              </div>
            </div>
            
            <div class="w-full lg:w-5/12 flex">
              <div class="w-full lg:w-1/2 px-6">
                <ul>
                  <li class="font-bold lg:text-md text-darktitle mb-6">
                    DISCOVER
                  </li>
                  <li>
                    <nuxt-link to="/"
                      class="text-xs lg:text-sm leading-none hover:text-brand dark:hover:text-brand text-gray-800 dark:text-gray-50"
                      >Getting Started</nuxt-link
                    >
                  </li>
                  <li class="mt-4">
                    <nuxt-link to="/"
                      class="text-xs lg:text-sm leading-none hover:text-brand dark:hover:text-brand text-gray-800 dark:text-gray-50"
                      >Partners</nuxt-link
                    >
                  </li>
                  <li class="mt-4">
                    <nuxt-link to="/"
                      class="text-xs lg:text-sm leading-none hover:text-brand dark:hover:text-brand text-gray-800 dark:text-gray-50"
                      >Resources</nuxt-link
                    >
                  </li>
                   <li class="mt-4">
                    <nuxt-link to="/"
                      class="text-xs lg:text-sm leading-none hover:text-brand dark:hover:text-brand text-gray-800 dark:text-gray-50"
                      >Our Team</nuxt-link
                    >
                  </li>
                </ul>
              </div>
              
              <div class="w-full lg:w-1/3 px-6">
                <ul>
                  <li class="font-bold lg:text-md text-darktitle mb-6">
                    DISCUSS
                  </li>
                  <li>
                    <nuxt-link to="/"
                      class="text-xs lg:text-sm leading-none hover:text-brand dark:hover:text-brand text-gray-800 dark:text-gray-50"
                      >Forum</nuxt-link
                    >
                  </li>
                  <li class="mt-4">
                    <nuxt-link to="/"
                      class="text-xs lg:text-sm leading-none hover:text-brand dark:hover:text-brand text-gray-800 dark:text-gray-50"
                      >Blogs</nuxt-link
                    >
                  </li>
                </ul>
              </div>
            </div>

            <div class="w-full lg:w-2/12 flex">
            <div class="w-full px-6">
                <ul>
                  <li class="font-bold lg:text-md text-darktitle mb-6">
                    SUPPORT
                  </li>
                  <li>
                    <nuxt-link to="/"
                      class="text-xs lg:text-sm leading-none hover:text-brand dark:hover:text-brand text-gray-800 dark:text-gray-50"
                      >Contact Us</nuxt-link
                    >
                  </li>
                  <li class="mt-4">
                    <nuxt-link to="/"
                      class="text-xs lg:text-sm leading-none hover:text-brand dark:hover:text-brand text-gray-800 dark:text-gray-50"
                      >FAQ</nuxt-link
                    >
                  </li>
                  <li class="mt-4">
                    <nuxt-link to="/"
                      class="text-xs lg:text-sm leading-none hover:text-brand dark:hover:text-brand text-gray-800 dark:text-gray-50"
                      >Terms</nuxt-link
                    >
                  </li>
                   <li class="mt-4">
                    <nuxt-link to="/"
                      class="text-xs lg:text-sm leading-none hover:text-brand dark:hover:text-brand text-gray-800 dark:text-gray-50"
                      >Privacy</nuxt-link
                    >
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="py-10 flex flex-col justify-center items-center">
        <p
          class="mt-6 mb-4 text-sm lg:text-sm leading-none text-gray-900 dark:text-gray-50"
        >
          Open-source MIT Licensed | Copyright © 2021 ExpressWeb JS
        </p>
        <nuxt-link to="/" class="flex">
          <img class="h-2 w-auto sm:h-6" src="/Logo.svg" />
        </nuxt-link>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style scoped></style>
