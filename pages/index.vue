<template>
<div class="relative bg-white overflow-hidden page">
  <hero />
  <features />
  <fiveS />
  <resources />
  <partner />
  <appFooter />
</div>

</template>

<script>
import hero from "../components/index/Hero.vue"
import features from "../components/index/Features.vue"
import fiveS from "../components/index/5s.vue"
import resources from "../components/index/Resources.vue"
import partner from "../layouts/Partner.vue"
import appFooter from "../layouts/footer.vue"



export default {
  components: {
    hero,
    features,
    fiveS,
    resources,
    partner,
    appFooter
  }
}
</script>

<style scoped>
.page {
  background-color: #FCFCFF;
}
</style>
