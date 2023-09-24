<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your firsty Vue.js App"/> -->
  <!-- <Homeone />
  <Pages /> -->
  <!-- <inputBoxes /> -->
  <!-- <ifElse /> -->
  <ForLoop />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import Homeone from './components/Home-one.vue'
// import Pages from './components/pages.vue'
// import inputBoxes from './components/inputboxes.vue';
// import ifElse from './components/if-else.vue';
import ForLoop from './components/For-loop.vue';

export default {
  name: 'App',
  components: {
    // HelloWorld,
    // Homeone,
    // Pages,
    // inputBoxes,
    // ifElse,
    ForLoop
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
}
</style>
