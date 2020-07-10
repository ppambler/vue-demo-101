<template>
  <div class="props">
    <!-- 这是 Props 的内部 -->
    {{ xxx }}
    <hr />
    {{ message }}
    <button @click="fn">call fn</button>
  </div>
</template>

<script>
export default {
  name: "Props",
  props: ["xxx", "message", "fn"]
};
</script>
<style lang="scss" scoped></style>