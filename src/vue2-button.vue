<script>
export default /*#__PURE__*/ {
  name: "Vue2Button", // vue component name
};
</script>

<template>
  <button class="vue2-button"><slot /></button>
</template>

<style scoped>
.vue2-button {
  color: white;
  font-weight: 500;
  font: 1.5em sans-serif;
  background-color: royalblue;
}
</style>
