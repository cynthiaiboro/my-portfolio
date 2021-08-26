<template>
  <div class="relative bg-white overflow-hidden page">
    <hero />
    <features />
    <portfolio />
    <tools />
    <contact />
  </div>
</template>

<script>
import hero from "../components/index/Hero.vue";
import features from "../components/index/Features.vue";
import portfolio from "../components/index/Portfolio.vue";
import tools from "../components/index/Tools.vue";
import contact from "../components/index/Contact.vue";

export default {
  components: {
    hero,
    features,
    tools,
    portfolio,
    contact
  }
};
</script>

<style scoped>
.page {
  background-color: #fcfcff;
}
</style>
