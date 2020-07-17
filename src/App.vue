<template>
  <div>
    <Header />
    <Intro />
    <Statistics />
  </div>
</template>

<script>
import Header from "./components/header.vue";
import Intro from "./components/intro.vue";
import Statistics from "./components/statistics.vue";

export default {
  name: "App",
  components: {
    Header,
    Intro,
    Statistics
  }
};
</script>

<style lang="scss">
@import "./styles/styles.scss";
</style>
