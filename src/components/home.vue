<template>
  <div class="container">
    <Navbar />
  </div>
</template>
<script>
import Navbar from "./navbar.vue";

export default {
  name: "Home",
  components: {
    Navbar
  }
};
</script>
<style>
:root {
  --theme-dark-blue: #242730;
  --theme-light-blue: #29323c;
  --theme-light-blue-hover: rgb(58, 65, 76);
  --theme-light-blue-hover-hover: rgb(106, 116, 133);
  --theme-light-blue-hover-text: rgb(211, 216, 224);
  --theme-label: rgb(106, 116, 133);
  --theme-text: rgb(160, 167, 180);
  --theme-dark-blue-gradient: linear-gradient(90deg, #29323c, #242730);
  --theme-lightGreen: #1fbad6;
  --theme-lightGreen30: #1fbad610;
}
.container {
  background: var(--theme-dark-blue-gradient);
  color: var(--theme-text);
  overflow: auto;
  height: 100vh;
  font-size: 15pt;
}
</style>
