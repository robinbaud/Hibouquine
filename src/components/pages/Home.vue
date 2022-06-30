<template>
  <BannerVue />
</template>

<script>
import BannerVue from "../molecules/Banner.vue";

export default {
  name: "Home",
  components: {
    BannerVue,
  },
};
</script>

<style scoped>
@import "~bootstrap/dist/css/bootstrap.css";
</style>
