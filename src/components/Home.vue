<template>
  <div class="home">
    <div class="container">
      <div class="image">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  .home {
    .container {
      margin: 24px;
      display: flex;

      .image {
        height: calc(100vh - 48px);
        width: 33.33vw;
        background-image: url(../assets/images/rahul.png);
        background-size: cover;
        background-position: center center;
      }
    }
  }
</style>
