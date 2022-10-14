<template>
<div>
  <h1>{{title}}</h1>
  <h2>{{subtitle}}</h2>
</div>
</template>

<script>


export default {
  data() {
    return {
      title: 'CSS Module Component',
      subtitle: 'This is forth exercise'

    }
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
  margin-top: 60px;
}
</style>
