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
  font-family: Lato;
  src: url(./assets/fonts/Lato-Black.woff);
  font-weight: 900;
}

@font-face {
  font-family: Lato;
  src: url(./assets/fonts/Lato-Bold.woff);
  font-weight: 700;
}

@font-face {
  font-family: Lato;
  src: url(./assets/fonts/Lato-Regular.woff);
  font-weight: 400;
}

body {
  margin: 0;
  font-family: Lato;
}

h1, h2, h3, h4, h5, h6 {
  font-family: Lato;
}

#app {
  
}
</style>
