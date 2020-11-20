<template>
 <header>
    <h1>{{ title }}</h1>
    <p>Welcome</p>
    <p>Some additional information here</p>
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