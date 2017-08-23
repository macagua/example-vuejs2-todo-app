<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
import TodoList from './components/TodoList'

export default {
  name: 'app',
  components: {
    // Add a reference to the TodoList component in the components property
    TodoList
  }
}
</script>

<style>
</style>
