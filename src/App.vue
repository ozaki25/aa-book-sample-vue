<template>
  <div id="app" class="container">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <PersonsTable />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import PersonsTable from './components/persons/PersonsTable';

export default {
  name: 'app',
  components: {
    HelloWorld,
    PersonsTable,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
