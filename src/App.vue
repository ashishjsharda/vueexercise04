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

<style lang="scss" module>
h1,

h2 {

  font-family: 'Avenir', Helvetica, Arial, sans-serif;

  text-align: center;

}

.title {

  font-family: 'Avenir', Helvetica, Arial, sans-serif;

  color: #2c3e50;

  margin-top: 60px;

}

.subtitle {

  color: #4fc08d;

  font-style: italic;

}
</style>
