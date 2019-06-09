<template>
  <div id="app">
    <div class="container">
      <img alt="Vue logo" src="./assets/logo.png">
      <AddTodo />
      <FilterTodo />
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos'
import AddTodo from './components/AddTodo'
import FilterTodo from './components/FilterTodos'

export default {
  name: 'app',
  components: {
    Todos,
    AddTodo,
    FilterTodo
  }
}
</script>

<style>
img{
  width: 90px;
}
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
