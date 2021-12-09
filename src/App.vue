<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style lang="scss">
@import "@/styles/global";
@import "@/styles/custom.scss";
@import "../node_modules/bootstrap/scss/bootstrap.scss";
</style>
