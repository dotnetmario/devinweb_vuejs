<template>
  <div id="app">
    <Main></Main>
  </div>
</template>

<script>
import Main from './components/main.vue';
import "./assets/css/main.css";

export default {
  name: 'App',
  components: {
    Main
  }
}
</script>

<style>
  html, 
  body {
      height: 100%;
  }

  .dev-bg-primary {
    background-color: rgb(246, 245, 248)
  }
</style>
