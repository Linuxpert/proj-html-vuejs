<template>
  <div id="containerHeader">
    <div class="logoMenu">
        <img src="../../src/assets/avada-music-logo.png" alt="">

        <!-- <i class="fas fa-bars"></i> -->
        <Slide>
            <a id="home" href="#">
            <span>Home</span>
            </a>
        </Slide>
    </div>

    <div class="center">
        <h1>
            <strong>
                Untold Stories
            </strong>
        </h1>

        <span class="subtitle">
            There is an untold story behind every favorite song.
        </span>

        <div class="headerBtn">
            <div class="album">
                <span>
                    LATEST ALBUM
                </span>
            </div>

            <div class="dates">
                <span>
                    LIVE DATES
                </span>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
import { Slide } from 'vue-burger-menu'

export default {
  name: 'MyHeader',
  components: {
    Slide
  }
}
</script>

<style lang="scss">

#containerHeader {
  background-image: url(../../src/assets/home_slider.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  height: 100vh;
//   height: 200px;
  .logoMenu{
      display: flex;
      justify-content: space-between;
      align-items: center;
      img {
          margin: 20px;
      }
    //   .fa-bars{
    //       margin: 20px;
    //       font-size: 40px;
    //       color: #fefefe;
    //       &:hover{
    //           cursor: pointer;
    //       }
    //   }
    .bm-burger-button{
        right: 36px;
    }
    .bm-menu{
        background-color: #ea4a56;
        right: 0;
        width: 100%;
    }
  }

  .center{
      text-align: center;
      margin-top: 10%;
      h1{
          font-size: 160px;
          color: #fefefe;
          font-family: 'Roboto', sans-serif;
      }
      .subtitle{
          font-size: 20px;
          color: #fefefe;
      }
  }

  .headerBtn{
      display: flex;
      justify-content: center;
      align-items: center;
      margin-top: 30px;
      .album{
          margin-right: 20px;
          padding: 10px 30px;
          background-color: #ea4a56;
          color: #fefefe;
          &:hover{
              background-color: #fefefe;
              color: #272b34;
              cursor: pointer;
          }
      }
      .dates{
          margin-right: 20px;
          padding: 10px 30px;
          border: 1px solid #fefe;
          color: #fefe;
          &:hover{
              background-color: #fefefe;
              color: #272b34;
              cursor: pointer;
          }
      }
  }
}
</style>
