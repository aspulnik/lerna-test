<template>
  <div id="app">
    <Header title="Test" />
    Bobcat<ksimg alt="Vue logo" style="height:300px" src="https://logos-download.com/wp-content/uploads/2018/04/Bobcat_logo_black_cercle-700x700.png">
    <Footer title="Test Footer" />
  </div>
</template>

<script>
import Header from '@customlibrary/Header'
import Footer from '@customlibrary/Footer'

export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
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
