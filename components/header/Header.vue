<template>
 <header>
    <h1>{{ title }}</h1>
    <p>Welcome111</p>
    <p>Some additional informat1ion here</p>
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