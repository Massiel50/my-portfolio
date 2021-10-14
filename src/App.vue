<template>
  <div id="app">
    <NavBar/>

    <About/>
    <Skills/>
    <Projects/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Projects from './components/Projects.vue'

export default {
  name: 'app',
  components: {
    NavBar,
    About,
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

body {
  min-height: 500px;
  padding-top: 50px;
  background-color: pink;
}

h2 {
  font-size: 4rem;
  font-style: oblique;
}
</style>
