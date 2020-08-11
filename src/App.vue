<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Nav class="mb-6" />
    <HelloWorld msg="We utilize Vue.js, TailwindCSS and Purge CSS to make app faster" class="text-center" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Nav from './components/Nav.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Nav
  }
}
</script>

<style src="./assets/styles/tailwind.css"/>
