<template>
  <HelloWorld msg="Jitu bhai is learning VUE JS by creating VUE App" :myExperience="`I am learning vue and it's a nice experience for me.`"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'Main',
  components: {
    HelloWorld
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 60px;
  padding-top: 5px;
  padding-bottom: 5px;
  border-style: groove;
  border-color: black;
  border-width: 5px;
  align-self: center;
  justify-content: center;
  justify-items: center;
  justify-self: center;
  align-content: center;
}
</style>
