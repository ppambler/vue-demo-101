<template>
  <div class="show-hook">
    <button @click="toggle">toggle</button>
    <hr />
    <Hook v-if="visible === true" />
  </div>
</template>

<script>
import Hook from "./Hook.vue";
export default {
  name: "ShowHook",
  components: { Hook },
  data() {
    return {
      visible: true
    };
  },
  methods: {
    toggle() {
      this.visible = !this.visible;
    }
  }
};
</script>

<style lang="scss" scoped></style>
