<template>
  <div id="app">
    <h1 class="text-center">Todo List</h1>
    <todo-list></todo-list>
  </div>
</template>

<script lang="js">
import TodoList from 'src/components/todolist/TodoList.vue'

export default {
  components: {
    TodoList
  },
  name: 'App'
}
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
