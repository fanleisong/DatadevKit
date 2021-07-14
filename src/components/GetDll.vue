<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      这是一个调用第三方应用的链接
      <a href="nav:" target="_blank" rel="noopener">Vue to a new APP</a>.
    </p>
   
  </div>
</template>

<script>
export default {
  name: 'GetDll',
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
