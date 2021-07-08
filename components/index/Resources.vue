<template>
  <div class="relative overflow-hidden">
    <div class="max-w-7xl mx-auto">
      <div class="bg-white text-darktitle py-20">
        <div
          class="grid grid-flow-col grid-cols-7 gap-4 max-w-7xl mx-auto py-8"
        >
          <div class="col-span-2">
            <p class="text-sm font-bold">Resources</p>
            <h1 class="text-3xl font-bold pb-3">
              A community built for <br />
              people like you
            </h1>
            <p class="text-sm pb-4">
              Sed convallis iaculis lacus a facilisis. Nullam dapibus quam at
              velit blandit porta. Ut sed metus sit amet libero maximus
              fringilla at eget mauris. Proin sit amet est sed ipsum varius
              tempor.
            </p>
            <div class="flex justify-between">
              <ul class="list-disc list-inside">
                <li class="py-2">Guides</li>
                <li class="py-2">Case Study</li>
                <li class="py-2">Events</li>
              </ul>

              <ul class="list-disc list-inside">
                <li class="py-2">Articles</li>
                <li class="py-2">Report</li>
                <li class="py-2">Forums</li>
              </ul>
            </div>
          </div>
          <div class="col-span-1"></div>
          <div class="col-span-4">
            <div class="bg-white rounded-lg blog-card grid grid-cols-2">
              <div class="h-full w-full relative">
                <img
                  class="h-full w-full relative"
                  src="../../assets/images/resources.png"
                  alt=""
                />

                <button
                  class="bg-primary absolute bottom-6 right-6 text-white px-4 py-2 rounded-lg"
                >
                  Engineering
                </button>
              </div>

              <div class="px-6 pt-8">
                <h3>FEATURED</h3>
                <h1 class="text-xl font-bold pb-3">
                  How we sped up syncing millions of rows per minute to Redshift
                  by 80%
                </h1>
                <div class="flex justify-between mb-3">
                  <div class="flex my-auto pt-2">
                    <img
                      class="my-auto"
                      src="../../assets/images/author.svg"
                      alt=""
                    />
                    <span class="text-sm my-auto ml-3"> Alex Igbokwe</span>
                  </div>

                  <p class="text-xs my-auto">MAY 10, 2021</p>
                </div>

                <p class="text-sm mb-5">
                  Lorem ipsum dolor sit amet, consectetur scing elit. Nunc,
                  pretium nunc vitae, tate. Vivamus arcu, facilisis at ut fe,
                  erat blandit. Viverra um, urna, in adipiscitellus imperdiet
                  eget mi eret quisque. Et nunc sapien massa lacus, semper
                  consectetur. Lorem ipsum dolor sit amet, sit a consectetur
                  adipiscing elit. Nunc, pretium nunc vitae, vulputate. Proin
                  sit amet est sed ipsum varius te....
                </p>
                <a href="#" class="text-primary text-sm">Read more</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.blog-card {
  box-shadow: 0px 6px 48px rgba(106, 150, 38, 0.16);
  border-radius: 24px;
}
</style>
