<template>
  <div id="app">
    <logo />
  </div>
</template>

<script>
import Logo from './components/logo.vue'

export default {
  name: 'App',
  components: {
    Logo,
  }
}
</script>

<style>
#app {
  text-align: center;
}
</style>