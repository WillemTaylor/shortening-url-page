<template>
  <div>
    <Link />
    <div class="stats-container">
      <h2>Advanced Statistics</h2>
      <p>
        Track how your links are performing across the web with our advanced
        statistics dashboard.
      </p>

      <div class="card">
        <div class="circle">
          <img :src="brand" />
        </div>
        <h3>Brand Recognition</h3>
        <p>
          Boost your brand recognition with each click. Generic links don't mean
          a thing. Branded links help instil confidence in your content.
        </p>
      </div>

      <div class="card">
        <div class="circle">
          <img :src="records" />
        </div>
        <h3>Detailed Records</h3>
        <p>
          Gain insights into who is clicking on your links. Konwing when and
          where people engage with your content helps inform better decisions.
        </p>
      </div>

      <div class="card">
        <div class="circle">
          <img :src="customizable" />
        </div>
        <h3>Fully Customizable</h3>
        <p>
          Improve brand awareness and content discoverability through
          customizable links, supercharging audience engagement.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import Link from "./link.vue";

export default {
  components: {
    Link
  },
  data() {
    return {
      brand: require("../assets/icon-brand-recognition.svg"),
      records: require("../assets/icon-detailed-records.svg"),
      customizable: require("../assets/icon-fully-customizable.svg")
    };
  }
};
</script>
