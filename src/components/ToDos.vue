<template>
<div>
<h1>My To Do List</h1>
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