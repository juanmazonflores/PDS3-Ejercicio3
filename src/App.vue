<template>
    <hello-world/>
  <hr/>
  <contador-simple/>
  <hr/>
  <to-do-list/>
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ContadorSimple from './components/ContadorSimple.vue'
import ToDoList from './components/ToDoList.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    ContadorSimple,
    ToDoList
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
  margin-top: 60px;
}
</style>
