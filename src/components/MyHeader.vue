<template>
  <div id="containerHeader">
    <div class="logoMenu">
        <img src="../../src/assets/avada-music-logo.png" alt="">

        <i class="fas fa-bars"></i>
    </div>
  </div>
</template>

<script>
// import MyHeader from '@/components/MyHeader.vue'

export default {
  name: 'MyHeader',
  components: {
    
  }
}
</script>

<style lang="scss">

#containerHeader {
  background-image: url(../../src/assets/home_slider.jpg);
  height: 200px;
  .logoMenu{
      display: flex;
      justify-content: space-between;
      align-items: center;
      img {
          margin: 20px;
      }
      .fa-bars{
          margin: 20px;
          font-size: 40px;
      }
  }
}
</style>
