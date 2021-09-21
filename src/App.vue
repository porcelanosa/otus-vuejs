<template lang="pug">
  #app
    img( alt="Vue logo" src="./assets/logo.png")
    HelloWorld(msg="Welcome to Otus Vue.js course")
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import('./assets/css/main.sass')

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="sass">
</style>
