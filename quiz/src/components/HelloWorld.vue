<template>
  <div class="hello" id="hello">
<p>HelloWorld component</p>
    <img alt="Vue logo" src="../assets/logo.png">

    <h1>{{ msg }}</h1>
    
    <p>{{myExperience}}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    myExperience: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}

#hello {
border-width: 5px;
border-color: paleturquoise;
border-style: dashed;
margin: 100px;
}

</style>
