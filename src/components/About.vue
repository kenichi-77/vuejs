<template>
  <div>
    <p>About</p>
    <input />
  </div>
</template>

<script>
export default {
  name: "About",
  destroyed() {
    console.log("destroyed");
  },
  activated() {
    console.log("activated");
  },
  deactivated() {
    console.log("deactivated");
  },
};
</script>
