<template>
  <div>
    <div class="container">
      <div class="row">

      <div class="col-12 col-lg-6">
        <div class="box">
          <img :src="require(`~/assets/${imgSrc5}`)" alt="">
          <img :src="require(`~/assets/${imgSrc3}`)" alt="">
          
        </div>
      </div>

      <div class="col-12 col-lg-6" v-for="i in 1" :key="`col-1-${i}`">
        <div class="box2">
          <br>
          <br>
          <br>
            <ul>
              <h2>Clouds</h2>
              <br><br><br>
              <h2>Side Scroll</h2>
              <br><br><br>
              <h2>Clocks</h2>
              <br><br><br>
              <h2>Temperature of my Apartment</h2>
              <br><br><br>
              <h2>Clown World</h2>
              <br><br><br>
              <h2>State Birds</h2>
            </ul>
        
        </div>
      </div>

      </div>
    </div>
  </div>


</template>



<script>
export default {
  data() {
        return{
            imgSrc2: "img/ferarridophinangel.jpeg",
            imgSrc3: "img/gracy-shared-a-drawing-with-you-39.png",
            imgSrc1: "img/couch.jpeg",
            imgSrc4: "img/gracy-shared-a-drawing-with-you-40.png",
            imgSrc5: "img/Happy-place.png",
            imgSrc6: "img/IMG_0696.png",
        }
    }
}
</script>



<style scoped lang="scss">
  .box{
    height: 100vh;
    background: white;
    color: black;
    margin-top: 100px;
    
  }
  .box2{
    height: 100%;
    background: black;
    color: white;
    margin: 0px;
    bottom: 10px;
    
  }

  img{
    width: 45%;
    padding: 10px;
    margin: 5px;
  }
</style>

