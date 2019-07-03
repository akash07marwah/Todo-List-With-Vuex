<template>
  <div id="app">
    <div class="container">
      <Todo />
      <FilterTodos />
    <Todos />    
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos.vue'
import Todo from './components/Todo.vue'
import FilterTodos from './components/filterTodos.vue'

export default {
  name: 'app',
  components: {
    Todos,
    Todo,
    FilterTodos
  }
}
</script>

<style>
  body{
    font-family: "Franklin Gothic Medium","Arial Narrow", Arial, sans-serif;
    line-height: 1.6;
    background:#f4f4f4;
  }
  .container{
    max-width:1100px;
    margin:auto;
    overflow:auto;
    padding: 0 2rem;
  }
</style>
