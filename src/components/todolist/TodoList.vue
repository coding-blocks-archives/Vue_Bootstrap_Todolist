<template>
  <div class="container">
    <div class="row">
      <div class="col"></div>
      <ul  class="col-6 ">
        <todo-list-item v-for="todo in todos" :todo="todo">
        </todo-list-item>
      </ul>
      <div class="col"></div>
    </div>
  </div>
</template>

<script lang="js">
  import TodoListItem from './TodoListItem'
  import Todo from 'src/models/todo'

  export default {
    components: {TodoListItem},
    name: 'todo-list',
    data () {
      return {
        todos: [
          new Todo('First task', false),
          new Todo('Second Task', true)
        ]
      }
    }
  }

</script>

<style>

</style>
