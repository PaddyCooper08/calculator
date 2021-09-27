<template>
  <div id="app">
    <Calculator></Calculator>
  </div>
</template>

<script>
import Calculator from "./components/Calculator.vue";

export default {
  name: "App",
  components: {
    Calculator,
  },
};
</script>

<style>
body {
  background: #31475e;
}
</style>
