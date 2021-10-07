<template>
  <div id="app">
    <NavBar/>
    <Skills/>
    <Projects/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Skills from './components/Skills.vue'
import Projects from './components/Projects.vue'

export default {
  name: 'app',
  components: {
    NavBar,
    Skills,
    Projects
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
