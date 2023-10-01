<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your firsty Vue.js App"/> -->
  <!-- <Homeone />
  <Pages /> -->
  <!-- <inputBoxes /> -->
  <!-- <ifElse /> -->
  <!-- <ForLoop /> -->
  <!-- <NewUser /> -->
  <!-- <ChildComponents /> -->
  <!-- <formulario /> -->
  <!-- <props /> -->
  <!-- <nonprops /> -->
  <watchers />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import Homeone from './components/Home-one.vue'
// import Pages from './components/pages.vue'
// import inputBoxes from './components/inputboxes.vue';
// import ifElse from './components/if-else.vue';
// import ForLoop from './components/For-loop.vue';
// import NewUser from './components/new-user.vue';
// import ChildComponents from './components/child-components.vue';
// import formulario from './components/formulario.vue';
// import props from './components/props.vue';
// import nonprops from './components/nonprops.vue';
import watchers from './components/watchers.vue';

export default {
  name: 'App',
  components: {
    // HelloWorld,
    // Homeone,
    // Pages,
    // inputBoxes,
    // ifElse,
    // ForLoop,
    // NewUser,
    // ChildComponents,
    // formulario,
    // props,
    // nonprops,
    watchers,
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
