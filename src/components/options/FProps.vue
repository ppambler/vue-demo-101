<template>
  <div class="f-props">
    {{ n }}
    <Props xxx="yyy" :message="n" :fn="fn" />
  </div>
</template>

<script>
import Props from "./Props.vue";
export default {
  name: "FProps",
  components: {
    Props
  },
  data() {
    return {
      n: "hi",
      yyy: 666
    };
  },

  methods: {
    add() {
      this.n += 1;
    },
    fn() {
      console.log("I am in Fprops, Props click me!");
    }
  }
};
</script>

<style lang="scss" scoped></style>
