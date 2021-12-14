<template>
  <div class="containerMain">
    <div class="music">

      <hr class="redBar">

      <h2>
        Music Is Life
      </h2>

      <hr class="bar">

      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto tempore dolores fugit maxime! Fuga, eligendi provident culpa ad, iste sint magni quam molestiae officiis error eos molestias, quisquam ipsum fugiat.
      </p>

    </div>

    <div class="bandNews">
      <h2>
        Latest Band News
      </h2>

      <hr class="bar">

      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto tempore dolores fugit maxime! Fuga, eligendi provident culpa ad, iste sint magni quam molestiae officiis error eos molestias, quisquam ipsum fugiat.
      </p>
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
p{
  text-align: center;
  width: 50%;
  margin: 30px auto;
  color: rgb(125, 123, 141);
}

.bandNews{
  background-color: rgb(37, 42, 51);
}
</style>
