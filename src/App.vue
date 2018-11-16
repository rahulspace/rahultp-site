<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from './components/Home'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>

@font-face {
  font-family: NotaSans;
  src: url(./assets/fonts/NotoSans-Bold.woff);
  font-weight: 700;
}

@font-face {
  font-family: NotaSans;
  src: url(./assets/fonts/NotoSans-Regular.woff);
  font-weight: 400;
}

body {
  margin: 0;
  font-family: NotaSans;
}

h1, h2, h3, h4, h5, h6 {
  font-family: NotaSans;
}

#app {
  
}
</style>
