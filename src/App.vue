<template>
  <div>
    <Header />
  </div>
</template>

<script>
import Header from "./components/header.vue";

export default {
  name: "App",
  components: {
    Header
  }
};
</script>

<style lang="scss">
@import "./styles/styles.scss";
</style>
