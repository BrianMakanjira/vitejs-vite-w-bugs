<template>
<div>
<h1>My To Do List</h1>
<ul>
<li v-bind:key="item.id" v-for="item in todoEntries">
<ToDoItem v-bind:todoItem="item" />
</li>
</ul>
</div>
</template>
<script>
import ToDoIte from '/components/ToDoItem'

export default {
  name: 'ToDos',
  components: {
    ToDoItem
  },
  props: [
    "todoEntries"
  ]
}
</script>