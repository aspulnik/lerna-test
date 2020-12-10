<template>
 <header>
    <h1>{{ title }}</h1>
    <p>Welcome1dd11</p>
    <p>Changed version</p>
  </header>
</template>

<script>
export default {
  name: 'Header',
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