<template>
  <div class="container">
    <VueSlickCarousel :arrows="true" :dots="true" class="slider">
      <div><h2>Health Care</h2></div>
      <div><h2>Internet</h2></div>
      <div><h2>Logistics</h2></div>
      <div><h2>Media and Entertainment</h2></div>
      <div><h2>Power</h2></div>
    </VueSlickCarousel>
  </div>
</template>
 
<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
 
  export default {
    name: 'MyComponent',
    components: { VueSlickCarousel },
  }
</script> 

<style scoped>
.container{
    display: flex;
    justify-content: space-around;
}
.slider{
    width: 300px;
}
h2{
    font-size: 30px;
}

</style>