<template>
<div id="app">
</ToDos>
</div>
</template>
<script>
import ToDos from '/components/ToDos'
export default: {
  name: 'App',
  components: {
    ToDos
  },
  data() {
    return {
      todoEntries: [
        {
          id:1,
          title: 'Lets Go',
          completed: false
        },
        {
          id:2,
          title: 'Rex Burketz',
          completed: false
        },
        {
          id:3,
          title: 'TouchDown',
          completed: false
        },

      ],
    }
  }
}
</script>
<style

></style>
