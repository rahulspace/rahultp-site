<template>
  <div class="home">
    <div class="container">
      <div class="image">
      </div>
      <div class="first-column">
        <div class="title">
          <h3>Hi There! I'm</h3>
          <h1>Rahul TP</h1>
          <h2>Developer</h2>
        </div>
        <div class="portfolio">
          <h2>Portfolio</h2>
        </div>
      </div>
      <div class="second-column">
        <div class="about">
          <h2>About me</h2>
        </div>
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
      padding: 24px;
      display: flex;
      background: #ffe4e4;

      .image {
        height: calc(100vh - 48px);
        width: 33.33vw;
        background-image: url(../assets/images/rahul.png);
        background-size: cover;
        background-position: center center;
      }

      .first-column {
        width: 33.33vw;
        margin-left: 24px;

        .title {
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          height: calc(50vh - 36px);
          margin-bottom: 24px;

          h3 {
            font-size: 20px;
            color: #666666;
            font-weight: 400;
          }

          h1 {
            font-size: 35px;
            color: #444444;
            font-weight: 900;
            margin-top: 15px;
            margin-bottom: 10px;
          }

          h2 {
            font-size: 23px;
            color: #ff7804;
            font-weight: 900;
          }
        }

        .portfolio {
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          height: calc(50vh - 36px);
          background: #ffffff;

          h2 {
            font-size: 30px;
            color: #ff7804;
            font-weight: 900;
          }
        }
      }

      .second-column {
        width: 33.33vw;
        margin-left: 24px;

        .about {
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          height: calc(50vh - 36px);
          background: #ffffff;

          h2 {
            font-size: 30px;
            color: #ff7804;
            font-weight: 900;
          }
        }
      }
    }
  }
</style>
