<template>
  <div id="app">
    <div class="cover-container d-flex h-100 p-3 mx-auto flex-column">
      <!-- Navebar top-->
      <headernav></headernav>

      <!-- content app convert on-->
      <mainconteriner></mainconteriner>

      <!-- Footer botton-->
      <footerb></footerb>
    </div>
  </div>
</template>
<script>
import headernav from "./components/headernav";
import mainconteriner from "./components/mainconteriner";
import footerb from "./components/footerb";
export default {
  name: "app",
  components: {
    headernav,
    mainconteriner,
    footerb,
  },
};
</script>
<style lang="scss">
@import "./assets/styles/_variables";
@import "./assets/styles/_bootstrap";
@import "./assets/styles/cover";
</style>
