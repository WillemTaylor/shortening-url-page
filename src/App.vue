<template>
  <div>
    <Header />
    <Intro />
    <Link />
  </div>
</template>

<script>
import Header from "./components/header.vue";
import Intro from "./components/intro.vue";
import Link from "./components/link.vue";

export default {
  name: "App",
  components: {
    Header,
    Intro,
    Link
  }
};
</script>

<style lang="scss">
@import "./styles/styles.scss";
</style>
