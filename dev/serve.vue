<script>
import Vue from "vue";
import Vue2Button from "@/vue2-button.vue";

export default Vue.extend({
  name: "ServeDev",
  components: {
    Vue2Button,
  },
});
</script>

<template>
  <div id="app">
    <vue2-button>click</vue2-button>
  </div>
</template>
