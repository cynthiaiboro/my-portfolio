<template>
  <div class="relative overflow-hidden">
    <div class="max-w-7xl mx-auto">
      <nav class="flex items-center justify-between flex-wrap bg-teal p-6 ">
        <div class="flex items-center flex-no-shrink text-white mr-6">
          <img class="h-12 w-auto mr-8" src="/Logo.svg" />
        </div>
        <div class="block sm:hidden">
          <button
            @click="toggle"
            class="flex items-center px-3 py-2 text-teal-lighter hover:outline-none hover:text-primary focus:outline-none"
          >
            <svg
              class="fill-current h-4 w-4"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <title>Menu</title>
              <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
            </svg>
          </button>
        </div>
        <div
          :class="open ? 'block' : 'hidden'"
          class="w-full flex-grow sm:flex sm:items-center sm:w-auto"
        >
          <div class="text-sm sm:flex-grow">
            
            <nuxt-link to="#portfolio" class="no-underline block mt-4 sm:inline-block font-bold sm:mt-0 text-primary hover:border-b-2 hover:scale-105 transform hover:border-primary transition mr-8">
              PROJECTS
            </nuxt-link>
            <nuxt-link to="#tools" class="no-underline block mt-4 sm:inline-block font-bold sm:mt-0 text-primary hover:border-b-2 hover:scale-105 transform hover:border-primary transition mr-8">
              TOOLS
            </nuxt-link>
            <nuxt-link to="#contact" class="no-underline block mt-4 sm:inline-block font-bold sm:mt-0 text-primary hover:border-b-2 hover:scale-105 transform hover:border-primary transition mr-8">
              CONTACT
            </nuxt-link>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    open: false
  }),
  methods: {
    toggle() {
      this.open = !this.open;
    }
  }
};
</script>

<style></style>
