<template>
<div>
  <h1>{{title}}</h1>
  <p>{{message}}</p>
</div>
</template>

<script>
export default {
  name: 'MyHeader',
  data () {
    return {
      title: 'Hey There',
      message: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped>
div {
  background-color:lightgray;
}
h1, h2 {
  color:rgb(0, 204, 255);
}
p {
  color:cadetblue;
}

</style>
