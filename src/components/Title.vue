<template>
    <h1> La mia prima app con Vue CLI! </h1>
</template>

<script>
export default {
  name: 'Title',
  props: {
      myTitle : String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
    text-align: center;
    font-size: 40px;
}
</style>
