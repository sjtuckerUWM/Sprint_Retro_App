<template>
  <div>
    <h1>Retrospective</h1>
  </div>
  <div>
    <label for="input">Input:</label>
    <input id="input">
    <input type="radio" id="straw">
    <label for="straw">straw</label>
  </div>
</template>

<script>
export default {
  name: 'UserInput',
  props: {
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
