<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <MainComponent />
    <ContectComponent />
<!--    {{ jsonData }}-->
  </div>
</template>

<script>
/* eslint-disable */

import MainComponent from "./components/MainComponent";
import ContectComponent from "./components/ContectComponent";

import json from "../data";

export default {
  name: "app",
  data() {
    return {
      // jsonData: JSON.parse(json)
    };
  },
  components: {
    MainComponent,
    ContectComponent
  },
  computed: {
    jsonData() {
      console.log(json);
      return json;
    }
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
