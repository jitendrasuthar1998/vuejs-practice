<template>
<div>
  <Header/>
  <Question-box/>
</div>
</template>

<script>
import Header from './components/Header.vue'
import QuestionBox from './components/QuestionBox.vue'
export default {
  name: 'Main',
  components: {
    Header,
    QuestionBox
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
  border-color: pink;
  border-width: 5px;
  align-self: center;
  justify-content: center;
  justify-items: center;
  justify-self: center;
  align-content: center;
}
</style>
