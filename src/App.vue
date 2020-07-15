<template>
  <div id="app">
    <home />
  </div>
</template>

<script>
import Home from "./components/Home";
export default {
  name: "App",
  components: {
    home: Home
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
  border: solid;
  height: 500px;
  width: 700px;
}
</style>
