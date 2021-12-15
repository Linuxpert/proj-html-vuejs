<template>
  <div class="footer">
    <!-- bottone news -->
    <div class="newBtn">
      <span class="textBtn">
        VIEW ALL LATEST NEWS
      </span>
    </div>

    <!-- container dates -->
    <div class="containerDates">
      <!-- jumbo basso -->
      <div class="jumbo1">

      </div>

      <div class="jumbo2">
        <div class="centerText">
          <h3 class="textJumbo2">
          "I just listened to it an said to myself, "Man, i really love thi album." Still, today, it just sounds so fresh. It sounds full of ideas. This guys knew what they were doing. They're good. And They're inventive. I haven't heard anything this year that's as inventive. I don't really expect to." 
          </h3>
          <div class="centerPlay">
            <img src="../../src/assets/band_interview_play_icon.png" alt="" class="play">
          </div>
          
        </div>
        
      </div>


      <!-- live dates -->
      <h2>
        Live Dates
      </h2>

      <hr class="bar">

      <p class="descBar">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto tempore dolores fugit maxime! Fuga, eligendi provident culpa ad, iste sint magni quam molestiae officiis error eos molestias, quisquam ipsum fugiat.
      </p>

      <!-- live places -->
      <div class="containerPlaces">
        <div class="boxPlace">
          <i class="fas fa-plus"></i>
          <span class="textPlace">
            17/08/2020 GEM FESTIVAL 2020 ANAKALIA, GEORGIA
          </span>
        </div>

        <div class="boxPlace">
          <i class="fas fa-plus"></i>
          <span class="textPlace">
            24/09/2020 GROOVIEFEST DOMINICAL REPUBLIC
          </span>
        </div>

        <div class="boxPlace">
          <i class="fas fa-plus"></i>
          <span class="textPlace">
            31/10/2020 OASI FESTIVAL 2020 MARRAKECH, MOROCCO
          </span>
        </div>

        <div class="boxPlace">
          <i class="fas fa-plus"></i>
          <span class="textPlace">
            07/11/2020 MOGA FESTIVAL - ESSAOURIA, MOROCCO
          </span>
        </div>

        <div class="boxPlace">
          <i class="fas fa-plus"></i>
          <span class="textPlace">
            10/12/2020 ENVISION FESTIVAL - UVITA, COSTA RICA
          </span>
        </div>

      </div>

      <!-- bottone LIVES -->
    <div class="newBtn">
      <span class="textBtn">
        VIEW ALL LIVE DATES
      </span>
    </div>
      

    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'MyFooter',
  components: {
    
  }
}
</script>

<style scoped lang="scss">
.footer{
  background-color: rgb(37, 42, 51);
}
.newBtn{
  background-color: #ea4a56;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 150px;
  cursor: pointer;
  .textBtn{
    color: #fefefe;
  }
  &:hover{
    background-color: #fefefe;
    .textBtn{
     color: #272b34;
  }
  }
}
.jumbo1{
  background-image: url(../../src/assets/home-testimonial-parallax.jpg);
  height: 200px;
}
.jumbo2{
  background-image: url(../../src/assets/home-testimonial-parallax.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: bottom;
  height: 746px;
  display: flex;
  justify-content: center;
  align-items: center;
  .textJumbo2{
    text-align: center;
    font-size: 36px;
    color: #fefefe;
  }
}
.centerText{
  width: 53%;
}
.centerPlay{
  display: flex;
  justify-content: center;
  margin-top: 50px;
  .play{
    cursor: pointer;
  }
}
.containerPlaces{
  width: 50%;
  margin: 0 auto;
  margin-bottom: 80px;
  .boxPlace{
    display: flex;
    align-items: center;
    background-color: rgb(50, 56, 68);
    margin-bottom: 10px;
    .fa-plus{
      margin-right: 10px;
      color: #fefefe;
      font-size: 10px;
      margin-left: 20px;
    }
    .textPlace{
      color: #ea4a56;
      padding: 15px;
    }
  }
}
</style>
