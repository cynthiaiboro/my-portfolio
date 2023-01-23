<template>
  <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="relative overflow-hidden">
    <div class="max-w-7xl mx-auto">
      <div
        class="relative z-10 pb-8 sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32"
      >
        <svg
          class="hidden lg:block absolute right-0 inset-y-0 h-full w-48 text-white transform translate-x-1/2"
          fill="currentColor"
          viewBox="0 0 100 100"
          preserveAspectRatio="none"
          aria-hidden="true"
        >
          <polygon points="50,0 100,0 50,100 0,100" />
        </svg>

        <main
          class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28"
        >
          <div class="sm:text-center lg:text-left">
            <h1
              class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl"
            >
              <span class="block xl:inline text-textGrey">Hi!</span>
              <p class="text-darktitle">I'M CYNTHIA DICKSON</p>
            </h1>
            <h1
              class="text-3xl tracking-tight font-extrabold text-gray-900 sm:text-3xl md:text-3xl mt-4"
            >
              <span class="block xl:inline text-primary">
                FRONTEND ENGINEER
              </span>
            </h1>
            <div
              class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start"
            >
              <p class="z-30">
                I’m a Frontend Engineer with over {{ year - 2019 }} years of
                experience providing high-impact web solutions for diverse
                industries. Skilled in designing, developing and testing
                web-based applications incorporating a range of technologies.
              </p>
            </div>
          </div>
        </main>
      </div>
    </div>
    <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
      <img
        class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full"
        src="../../assets/images/product-evc.gif"
        alt=""
      />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>

<style></style>
