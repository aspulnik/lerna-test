<template>
 <footer>
    <h1>{{ title }}</h1>
    <p>Posted by XXX v4.1131111a</p>
    <p>Some additional information here</p>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    title: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
</style>