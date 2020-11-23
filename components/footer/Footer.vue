<template>
 <footer>
    <h1>{{ title }}</h1>
    <p>Buh bye !!!!1lerna11k!</p>
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