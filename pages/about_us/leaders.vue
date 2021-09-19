<template>
<div class="contain">
   <div class="all">
        <h3>Leaders</h3>
        <p>Bizzcon is the pioneer of organised recruitment in India. Our roots in management consulting enable us to bring a unique approach to recruitment.</p>
        <div class="view"></div>
  </div>
  <div class="info">
      <h6>We have an unmatched experience in helping companies recognize, grow, and promote real talent. It is important that we follow the same principles ourselves.
</h6>
  </div>
<div class="leaders">
  <div class="team">
    <div class="image">
      <img :src="`https://avatars.dicebear.com/v2/avataaars/john.svg?options[mood][]=happy`" alt="" class="img1">
    </div>
    <h3>Shiv Agrawal</h3>
    <h4>Managing Director</h4>
    <p>Shiv is a management graduate from the London Business School and possesses over 20 years of experience in the executive search and selection industry.</p>
  </div>

  <div class="team">
    <div class="image">
      <img :src="`https://avatars.dicebear.com/v2/avataaars/jenny.svg?options[mood][]=happy`" alt="" class="img1">
    </div>
    <h3>Ratna Gupta</h3>
    <h4>Senior Director</h4>
    <p>Shiv is a management graduate from the London Business School and possesses over 20 years of experience in the executive search and selection industry.</p>
  </div>

  <div class="team">
    <div class="image">
      <img :src="`https://avatars.dicebear.com/v2/avataaars/json.svg?options[mood][]=happy`" alt="" class="img1">
    </div>
    <h3>BM Gupta</h3>
    <h4>Senior Director & CFO</h4>
    <p>Shiv is a management graduate from the London Business School and possesses over 20 years of experience in the executive search and selection industry.</p>
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
  text-align: center;
}

.image .img1{
  width: 40%;
  background: rgb(226, 226, 226);
  border-radius:1000px ;

}

.leaders{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.team{
  text-align: center;
  padding: 10px;
  background: rgb(243, 241, 241);
  margin: 10px;
}

.team h4{
  color: rgb(167, 163, 163);
}

@media screen and (max-width: 900px) {
.leaders{
  flex-direction: column;
}

}

</style>