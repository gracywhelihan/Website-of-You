<template>
    <div>
    <div class="container">
      <div class="row">

      <div class="col-12 col-lg-6">
        <div class="box">
            <p>Hello my name is Gracy! The is my portfolio and this is my about page. There will be more here soon. </p>
        </div>
      </div>

      <div class="col-12 col-lg-6" v-for="i in 1" :key="`col-1-${i}`">
        <div class="box2">
          
           
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
        }
    },
    methods: {
    
    }
}
</script>

<style scoped lang="scss">
  .box{
    height: 100vh;
    background: white;
    color: black;
    margin-top: 100px;
    padding: 20px;
    
  }
  .box2{
    height: 100%;
    background: black;
    color: white;
    margin: 0px;
    bottom: 10px;
    
  }


</style>