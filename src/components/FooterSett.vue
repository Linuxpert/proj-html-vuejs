<template>
  <div class="footerBox">
    <a class="footerMenu" :href="details.urls">
    <span class="textMenu">{{details.text}}</span>
    </a>
  </div>
</template>

<script>


export default {
  name: 'FooterSett',
  props:{
      details:Object
  },
  components: {
    
  },
  
}
</script>

<style  lang="scss">
    .footerMenu{
        text-decoration: none;
        .textMenu{
            color: rgb(125, 123, 141);
            margin: 0 10px;
            &:hover{
                color: #fefefe;
            }
        }
    }
</style>
