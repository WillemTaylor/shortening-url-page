<template>
  <header class="header-container">
    <div>
      <img :src="src" />
    </div>

    <nav role="navigation">
      <div id="menuToggle">
        <input type="checkbox" />
        <span></span>
        <span></span>
        <span></span>
        <ul id="menu">
          <a v-scroll-to="'#features'">
            <li>Features</li>
          </a>
          <a v-scroll-to="'#pricing'">
            <li>Pricing</li>
          </a>
          <a v-scroll-to="'#resources'">
            <li>Resources</li>
          </a>
          <hr />
          <a v-scroll-to="'#login'">
            <li>Login</li>
          </a>
          <a v-scroll-to="'#signup'">
            <button class="button">Sign Up</button>
          </a>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  data() {
    return {
      src: require("../assets/logo.svg")
    };
  }
};
</script>
