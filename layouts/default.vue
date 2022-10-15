<template>
    <div class ="app">
    <nav>
     <div>
       <div class="container">
       <div class="row">

        <div class="col-12">
           <h1>Gracy Whelihan</h1>
        </div>

         <div class="col-12 col-lg-1">
           <NuxtLink to="/">Home</NuxtLink>
        </div>

         <div class="col-12 col-lg-2" :key="`col-1-0`">
          <NuxtLink to="/about">About</NuxtLink>
        </div>

        <div class="col-12 col-lg-2" :key="`col-1-1`">
          <p>:)</p>
        </div>

      </div>
    </div>
  </div>
    </nav>

        <Nuxt />
    </div>
</template>

<style scoped lang="scss">
  .app{
    height: 100vh;
    background:white;
    color: black;
  }
  
</style>