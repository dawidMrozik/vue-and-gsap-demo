<template>
  <div id="app">
    <Scene />
  </div>
</template>

<script>
import Scene from './Scene'
import { gsap } from 'gsap'

export default {
  name: 'App',
  components: {
    Scene
  },
  created: function() {
    console.log(gsap)
    console.log(this.$refs.svg)
  }
}
</script>

<style>
#app {
  height: 100%;
  width: 100%;
  padding-top: 2em;
}
</style>
