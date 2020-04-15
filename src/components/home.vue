<template>
  <div class="container center"></div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      active: "home"
    };
  },
  methods: {
    activate(page) {
      this.active = page;
    }
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
.nav-item {
  padding: 15px;
  cursor: pointer;
  transition: all 0.3s ease;
  font-weight: 300;
}
.nav-item:hover {
  background: #ffffff30;
}
.nav-item.active {
  background: #ffffff30;
}
.content {
  padding: 15px;
  margin-top: 15px;
  font-size: 14pt;
  text-align: center;
}
.inner {
  height: 500px;
  width: 800px;
  background: var(--theme-dark-blue);
}
.container {
  background: var(--theme-dark-blue-gradient);
  color: var(--theme-text);
  overflow: auto;
  height: 100vh;
  font-size: 15pt;
}
.center-h {
  display: flex;
  justify-content: center;
}
.center-v {
  display: flex;
  align-items: center;
}
.center {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
