<template>
  <div id="app">
    <div class="container">
      <AddTodos/>
      <FilterTodos/>
      <Todo/>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Todo from "./components/Todo.vue";
import AddTodos from "./components/AddTodos.vue";
import FilterTodos from "./components/FilterTodos.vue";


export default {
  name: 'App',
  components: {
    Todo,
    AddTodos,
    FilterTodos
  }
}
</script>

<style>
body{
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container{
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
