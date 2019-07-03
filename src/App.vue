<template>
  <div id="app">
    <GetToDo></GetToDo>
    <CurrentToDos></CurrentToDos>
    <CompletedToDos></CompletedToDos>
  </div>
</template>

<script>
import GetToDo from "./components/GetToDo.vue";
import CurrentToDos from "./components/CurrentToDos.vue";
import CompletedToDos from "./components/CompletedToDos.vue";

export default {
  name: "ToDo",
  components: {
    GetToDo,
    CurrentToDos,
    CompletedToDos
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
