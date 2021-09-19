<template>
<div class="contain">
  <div class="all">
        <h3>Life at Bizzcon</h3>
        <p>Bizzcon is the pioneer of organised recruitment in India. Our roots in management consulting enable us to bring a unique approach to recruitment.</p>
        <div class="view"></div>
      </div>
      <div class="info">
        <h1>The Bizzcon Advantage</h1>
        <p>ABC Consultants is a preferred talent acquisition partner to Multinationals and leading Indian businesses. This combined with our role as trusted consultants for Indian professionals translates into our core capability – Building Careers. Building Organisations.</p>
      </div>
      <div class="life">
        <div class="flex">
          <div class="info1">
          <h2>Inside our office</h2>
          <p>While our practices are structured nationally, our teams are spread across locations. To interact and bond, we travel as well as connect virtually. At work, some of us have individual corners to decorate and call our own, while others float and occupy ‘Hot Seats’. Our offices are spacious , comfortable and are equipped with necessary comforts and resources. We make it a point to decorate our offices to reflect our unique culture and aesthetics.</p>
        </div>
        <div class="info2">
          <h2>Life at Bizzcon</h2>
          <p>Flexi-timings and work from home arrangements enable us to balance our professional and personal priorities. We rarely miss an opportunity to celebrate festivals and birthdays, enjoy the company of li’l ones on our kids day, go for team outings, and play pranks. Our day-outings and offsites are a blast and everyone eagerly looks forward to being part of the Annual Conference. When we’re not doing all of this, we connect with clients and candidates and work as well.</p>
        </div>
        </div>
        <div class="flex2">
                  <img :src="require(`@/assets/office.jpg`)" alt="" class="image1">

          <div class="info3">
          <h2>Why join Bizzcon</h2>
          <p>At the end of the day, if we’re able to keep clients , candidates and employees happy and delighted , it’s worth all the effort put in. If you are target oriented, hungry for success and want to carve out a niche for yourself, your search ends here. We invite you to be part of our roller coaster ride, where the journey is tough, but the thrill is awesome.
              Building Careers. Building Organisations. That’s what we do best. We are ABC.</p>
        </div>
        </div>
        
      </div>
      
</div>
  
</template>

<script>
export default {

}
</script>

<style scoped>
.all{
  background: url(https://images.unsplash.com/photo-1581299327801-faeb40ea459e?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=871&q=80);
  text-align: left;
  color: white;
  padding: 30px;
}

.all h2{
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

.view{
  background: rgb(158, 158, 0);
  height: 10px;
  width: 80px;
}

.info{
  padding: 20px;
}

.info1{
  text-align: justify;
  padding: 20px;
  background: rgb(243, 242, 242);

}
.info1 p{
  font-size: 20px;
}
.info1 h2{
  font-size: 35px;

}
.info2{
  text-align: right;
  padding: 20px;
  background: white;
}
.info2 p{
  font-size: 20px;
  text-align: justify;
}
.info2 h2{
  font-size: 35px;

}

.image1{
  width: 40%;
}
.info3{
  text-align: justify;
  padding: 20px;
  background: rgb(243, 242, 242);

}
.info3 p{
  font-size: 20px;
}
.info3 h2{
  font-size: 35px;

}

.flex{
  display: flex;
}

.flex2{
  display: flex;
}

@media screen and (max-width: 900px) {
.flex{
  flex-direction: column;
}
.flex2{
  flex-direction: column;
}
.image1{
  width: 100%;
}
}

</style>