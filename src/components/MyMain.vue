<template>
  <div class="containerMain">
    <div class="music">

      <hr class="redBar">

      <h2>
        Music Is Life
      </h2>

      <hr class="bar">

      <p class="descBar">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto tempore dolores fugit maxime! Fuga, eligendi provident culpa ad, iste sint magni quam molestiae officiis error eos molestias, quisquam ipsum fugiat.
      </p>

    </div>

    <div class="bandNews">
      <h2>
        Latest Band News
      </h2>

      <hr class="bar">

      <p class="descBar">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto tempore dolores fugit maxime! Fuga, eligendi provident culpa ad, iste sint magni quam molestiae officiis error eos molestias, quisquam ipsum fugiat.
      </p>

      <div class="containerNews">
        <div class="boxLeft">
          
            
            <div class="techCard">
              <div class="boxHover">
                <h3 class="info">
                  Tecnology and music
                </h3>
                <img src="../../src/assets/blog_music_techo.jpg" alt="">
              </div>
              <h3 class="boxTitle">Tecnology and music</h3> 
              <p class="description">Sed sit amet sem turpis. CUrabitur cursor lacinia est at interdum risus id condimentum.</p>
            </div>
          
          

          <div class="boxMiddle">
            <div class="middleCard">
              <img src="../../src/assets/blog-post3.jpg" alt="">
              <h3 class="boxTitle">Tecnology and music</h3> 
              <p class="description">Sed sit amet sem turpis. CUrabitur cursor lacinia est at interdum risus id condimentum.</p>
            </div>

            <div class="middleCard">
              <img src="../../src/assets/blog-post4.jpg" alt="">
              <h3 class="boxTitle">Tecnology and music</h3> 
              <p class="description">Sed sit amet sem turpis. CUrabitur cursor lacinia est at interdum risus id condimentum.</p>
            </div>
          </div>

          <div class="rockCard">
            <img src="../../src/assets/blog_flavor_rock-1200x600.jpg" alt="">
            <h3 class="boxTitle">Tecnology and music</h3> 
            <p class="description">Sed sit amet sem turpis. CUrabitur cursor lacinia est at interdum risus id condimentum.</p>
          </div>

        </div>

        <div class="boxRight">
          <div class="oldschoolCard">
            <img src="../../src/assets/blog-post1-400x600.jpg" alt="">
            <h3 class="boxTitle">Tecnology and music</h3> 
            <p class="description">Sed sit amet sem turpis. CUrabitur cursor lacinia est at interdum risus id condimentum.</p>
          </div>

          <div class="legendCard">
            <img src="../../src/assets/blog-post2-400x600.jpg" alt="">
            <h3 class="boxTitle">Tecnology and music</h3> 
            <p class="description">Sed sit amet sem turpis. CUrabitur cursor lacinia est at interdum risus id condimentum.</p>
          </div>
        </div>
      </div>
    </div>
    
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'MyMain',
  components: {
    
  }
}
</script>

<style lang="scss">
.music{
  background-color: rgb(50, 56, 68);
  height: 300px;
}
.redBar{
  border: 10px solid #ea4a56;
  width: 30%;
  margin-right: auto;
  margin-left: auto;
}
h2{
    color: #fefefe;
    text-align: center;
    padding: 60px 0 10px 0;
    font-size: 60px;
  }
.bar{
  border: 1px solid rgb(68, 78, 98);
  width: 25%;
  margin-right: auto;
  margin-left: auto;
  margin-top: 10px ;
}
.descBar{
  text-align: center;
  width: 50%;
  margin: 30px auto;
  color: rgb(125, 123, 141);
}

.bandNews{
  background-color: rgb(37, 42, 51);
}
.containerNews{
  margin: 30px auto;
  width: 70%;
  display: flex;
  justify-content: center;
}
.boxLeft{
  display: flex;
  flex-direction: column;
  width: 60%;
  
}
.boxHover{
  background-color: #ea4a56;  
  .info{
    text-align: center;
    vertical-align: middle;
  }
}
.techCard{
  width: 100%;
  background-color: rgb(50, 56, 68);
  
  
  img{
    object-fit: cover;
    width: 100%;
    height: 200px;
  }
  
}
.boxMiddle{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.middleCard{
  margin-top: 30px;
  width: 48%;
  background-color: rgb(50, 56, 68);
  img{
  object-fit: cover;
  width: 100%;
  height: 440px;
  }
}
.rockCard{
    margin-top: 30px;
    background-color: rgb(50, 56, 68);
    width: 100%;
    img{
      object-fit: cover;
      width: 100%;
      height: 200px;
    }
}
.boxRight{
  display: flex;
  flex-direction: column;
  width: 25%;
  justify-content: space-between;
  margin-left: 30px ;
}
.oldschoolCard{
  background-color: rgb(50, 56, 68);
  width: 100%;
  img{
      object-fit: cover;
      width: 100%;
      height: 510px;
    }
}
.legendCard{
  background-color: rgb(50, 56, 68);
  width: 100%;
  img{
      object-fit: cover;
      width: 100%;
      height: 400px;
    }
}
.boxTitle{
  color: #ea4a56;
  margin: 15px 0 5px 10px;
}
.description{
  color: #7d7b8d;
  margin: 0 0 10px 10px;
}

</style>
