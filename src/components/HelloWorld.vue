<template>
<div>
  <b-button variant="success" size="lg">Mi Boton</b-button>
  <b-button :pressed="false" variant="warning">Mi Boton</b-button>
  <b-button variant="primary" size="sm">Mi Boton</b-button>
</div>

</template>

<script>
export default {
  name: 'HelloWorld',
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
