<template>
  <div id="app1">
    <showHook />
    <hr />
    <FProps />
  </div>
</template>

<script>
import ShowHook from "./components/options/ShowHook.vue";
import FProps from "./components/options/FProps.vue";
export default {
  name: "App",
  components: {
    ShowHook,
    FProps
  }
};
</script>

<style lang="scss"></style>
