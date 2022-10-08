<script>
export default /*#__PURE__*/ {
  name: "Vue2Button",
  props: {
    bgColor: {
      type: String,
      default: "royalblue",
    },
    txColor: {
      type: String,
      default: "white",
    },
  },
};
</script>
  
<template>
  <button
    class="vue2-button"
    :style="{ 'background-color': bgColor, color: txColor }"
  >
    <slot />
  </button>
</template>

<style scoped>
.vue2-button {
  padding: 5px 12px;
  border-radius: 8%;
  border: none;
  color: white;
  font-weight: bold;
  background-color: royalblue;
  font-family: monospace, sans-serif;
  text-decoration: none;
  cursor: pointer;
  transition: transform 0.2s;
}
.vue2-button:hover {
  transform: scale(1.2);
}
</style>
