<template>
  <div>
    <img
      class="logo"
      src="../../assets/img/logo.png"
    >
    <h1>{{ hello }}</h1>
  </div>
</template>

<script>
export default {
  data () {
    return {
      hello: 'Hello World'
    }
  }
}
</script>

<style module>
.logo {
    height: 150px;
    width: 150px;
}
</style>
