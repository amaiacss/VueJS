<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <AboutPage />
</template>

<script>
import AboutPage from './modules/pokemon/pages/AboutPage';

export default {
  name: 'App',
  components: {
    // definir el módulo para despues usarlo
    AboutPage
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
