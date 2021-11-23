<template>
  <div>
    <Title />
    <Main />
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Main from './components/Main.vue'


export default {
  name: 'App',
  components: {
    Title,
    Main
  }
}
</script>

<style>
  .container {
    width: 70%;
    margin: 0 auto;
  }

  .jumbotron {
    height: 500px;
    width: 100%;
  }
</style>
