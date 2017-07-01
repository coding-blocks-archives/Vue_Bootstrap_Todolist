<template>
  <li class="list-group-item">
    <input type="checkbox" :checked="todo.done" class="col-1">
    <span class="col-8">{{todo.task}}</span>
  </li>
</template>

<script lang="js">
  export default {
    name: 'todo-list-item',
    props: [
      'todo'
    ]
  }
</script>
