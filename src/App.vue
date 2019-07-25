<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <MainComponent/>
    <ContectComponent/>
  </div>
</template>

<script>
import MainComponent from "~/components/MainComponent";
import ContectComponent from "~/components/ContectComponent";

export default {
  name: "app",
  components: {
    MainComponent,
    ContectComponent
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
