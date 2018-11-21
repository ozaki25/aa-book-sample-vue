<template>
  <div  class="container">
    <div id="app">
      <img alt="Vue logo" src="./assets/logo.png" />
      <HelloWorld msg="Welcome to Your Vue.js App" />
    </div>
    <div class="panel panel-default">
      <div class="panel-heading">Vue Sample</div>
      <div class="panel-body">
        <PersonsForm />
      </div>
      <PersonsTable />
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import PersonsTable from './components/persons/PersonsTable';
import PersonsForm from './components/persons/PersonsForm';

export default {
  name: 'app',
  components: {
    HelloWorld,
    PersonsTable,
    PersonsForm
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
