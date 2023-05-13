<template>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Home />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home'
export default {
  name: 'App',
  components: {
    HelloWorld,
    Home
  }
}
</script>


