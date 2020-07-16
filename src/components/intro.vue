<template>
  <div class="intro-container">
    <img :src="src" />
    <h1>More than just shorter links</h1>
    <p>
      Build your brand's recognition and get detailed insights on how your links
      are performing.
    </p>
    <button class="button">Get Started</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      src: require("../assets/illustration-working.svg")
    };
  }
};
</script>
