<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Help us develop our landing page!</p>
    <a href="https://github.com/set-traces/set-traces-landing">Read more here</a>
    <h3>Want to contribute to our product? Read more about our product here:</h3>
    <a href="https://github.com/set-traces/set-traces-frontend/wiki">Script writing tool for Abakusrevyen</a>
    <p style='margin: 4em'>
    </p>
    <p>
        - Eirik & Jakob
    </p>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
