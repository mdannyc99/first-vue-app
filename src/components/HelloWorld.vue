<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>{{ text }}</h2>
    <div style="background: green">
      <myComponent></myComponent>
    </div>
    
  </div>
</template>

<script>
import myComponent from './myComponent.vue'

export default {
  name: 'HelloWorld',
  components: {
    myComponent
  },
  props: {
    msg: String
  },
  data(){
    // Variables para usar en el <template> con {{ nom_variable }}
    return {
      text: "Welcome to my first vue app."
    }
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
