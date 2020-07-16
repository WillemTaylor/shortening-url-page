<template>
  <div class="link-container">
    <img :src="src" />
    <input type="text" placeholder="Shorten a link here..." />
    <button class="button">Shorten it!</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      src: require("../assets/bg-shorten-mobile.svg")
    };
  }
};
</script>
