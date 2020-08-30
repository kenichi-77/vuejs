<template>
  <div>
    <slot></slot>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "test",
      user: "aaaa",
    };
  },
  props: ["headerText"],
};
</script>
<!--
<style scoped>
div {
  border: 1px solid blue;
}
h1 {
  color: red;
}
</style>
-->

