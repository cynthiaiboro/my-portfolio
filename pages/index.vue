<template>
<div class="relative bg-white overflow-hidden page">
  <hero />
  <features />
  <fiveS />
</div>

</template>

<script>
import hero from "../components/index/Hero.vue"
import features from "../components/index/Features.vue"
import fiveS from "../components/index/5s.vue"
export default {
  components: {
    hero,
    features,
    fiveS
  }
}
</script>

<style scoped>
.page {
  background-color: #FCFCFF;
}
</style>
