<template>
  <div id="app" class="container">
    <img alt="Vue logo" src="./assets/logo.png" class="logo">
    <todo-list></todo-list>
  </div>
</template>

<script>
import TodoList from './components/TodoList'

export default {
  name: 'app',
  components: {
    TodoList
  }
}
</script>

<style lang="scss">
*{
  box-sizing: border-box;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  font-size: 24px;
  margin-top: 60px;
}
.container{
  max-width: 600px;
  margin: 0px auto;
}

.logo{
  height: 75px;
  display: block;
  margin: 20px auto;
}
</style>
