<template>
  <div id="app">
    <Helloworld />
  </div>
</template>

<script>

import Helloworld from './components/HelloWorld.vue'

export default {
  components: {
    Helloworld
  },
  data () {
    return {
      message: 'Hello World'
    }
  }
}
</script>

<style>
#app {
  font-size: 18px;
  font-family: 'Roboto', sans-serif;
  color: blue;
}
</style>
