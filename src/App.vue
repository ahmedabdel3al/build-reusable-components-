<template>
  <div id="app">
    <toggle-input v-model="checked" />
  </div>
</template>

<script>
import ToggleInput from "./components/ToggleInput";

export default {
  name: "App",
  components: {
    ToggleInput
  },
  data() {
    return {
      checked: false
    };
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
