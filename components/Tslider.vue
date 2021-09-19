<template>
  <div class="container">
    <VueSlickCarousel :arrows="true" :dots="true" class="slider">
      <div class="text">
          <p>"ABC has been a valuable recruitment partner for us in helping us bring some of the best talent on board. I know when I interview an ABC recommended candidate, they would already have been vetted as a suitable fit within our company and its culture. There are a very few professional "Head Hunters" in this industry who bring competence to the table with a very positive attitude in an extremely friendly manner. They provide exceptional guidance throughout each stage of the recruitment process and are always keen to give advice while showing genuine interest in our progress. Highly recommended for any future collaboration as ABC has displayed a touch of class which is very rare experience with other recruitment consultants. Working with ABC is an absolute pleasure."</p>
          <p>-Adarsh Mishra | Chief Human Resource Officer | Panasonic India (P) Ltd.</p>
      </div>
      <div class="text">
          <p>"We have been working with ABC for long. They understand Unilazer businesses and our requirements extremely well. They have dedicated teams to service all sectors like Development, Sports, Media and Education, that are customer friendly and responsive. We wish to nurture this relationship going forward."</p>
          <p>-Ronnie Screwvala | Founder UTV Group | Unilazer Ventures and Swades Foundation</p>
          </div>
      <div class="text">
          <p>"Our Association with ABC goes back more than a decade and a half. The core strength of this sustained relationship, has been ABC’s ability to gain, contextual insights, both at the business & cultural level at Dabur and provide the best Talent fit across varied and diverse requirements."</p>
          <p>-V.Krishnan | Executive Director | Dabur India Limited</p>
          </div>
      <div class="text">
          <p>"ABC has been a strategic partner in helping us set up a great start-up team at Arvind Fashion Brands and Arvind Sports Lifestyle. The team understands the space; but more importantly how our organization wanted to carve out a niche for itself in a cluttered marketplace for talent. It is on the backbone built by ABC that we were able to build a strong team that now delivers superior value."</p>
          <p>-Rajiv Mehta | Chief Executive Officer | Arvind Sports Lifestyle Ltd.</p>
          </div>
      <div class="text">
          <p>"ABC Consultants have the ability to understand your business context, the role requirements and specifics of the job. Coupled with this their national presence, hands-on approach, and an internal process rigor ensures accurate screening and shortlisting of candidates. They have delivered search results that are quick and precise to the organisation’s needs. This unique approach makes them a valued partner for Tata Sky."</p>
          <p>-Sangram Chavan | Chief Human Resource Officer | Tata Sky
</p>
          </div>
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
    width: 80%;
      word-wrap: break-word;


}
h2{
    font-size: 30px;
}

.text{
}

</style>