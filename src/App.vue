<template lang="pug">
  #app
    MarkDownEditor
</template>

<script>
import MarkDownEditor from './components/MarkDownEditor.vue'

export default {
  name: 'App',
  components: {
    MarkDownEditor
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
