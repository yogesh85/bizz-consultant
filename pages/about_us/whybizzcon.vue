<template>
  <div class="contain">
    <div class="all">
          <h2>Why Bizzcoin</h2>
          <p>Bizzcon is the pioneer of organised recruitment in India. Our roots in management consulting enable us to bring a unique approach to recruitment.</p>
          <div class="view"></div>
    </div>
    <div class="info">
      <h2>The Bizcon Advantage</h2>
      <p>ABC Consultants is a preferred talent acquisition partner to Multinationals and leading Indian businesses. This combined with our role as trusted consultants for Indian professionals translates into our core capability – Building Careers. Building Organisations.</p>
      <div class="cards">
      <div class="cards">
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <h3>50+</h3>
              <h4>Years of Market leadership</h4>
            </div>
            <div class="flip-card-back">
              <h4>Market leader for over four decades</h4>
              <p>• Pioneer of organised recruitment in India</p>
              <p>• Unparalleled network and understanding of the Indian Market</p>
            </div>
          </div>
        </div>
      </div>
      <div class="cards">
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <h3>50+</h3>
              <h4>Years of Market leadership</h4>
            </div>
            <div class="flip-card-back">
              <h4>Market leader for over four decades</h4>
              <p>• Pioneer of organised recruitment in India</p>
              <p>• Unparalleled network and understanding of the Indian Market</p>
            </div>
          </div>
        </div>
      </div>
      <div class="cards">
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <h3>50+</h3>
              <h4>Years of Market leadership</h4>
            </div>
            <div class="flip-card-back">
              <h4>Market leader for over four decades</h4>
              <p>• Pioneer of organised recruitment in India</p>
              <p>• Unparalleled network and understanding of the Indian Market</p>
            </div>
          </div>
        </div>
      </div>
      <div class="cards">
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <h3>50+</h3>
              <h4>Years of Market leadership</h4>
            </div>
            <div class="flip-card-back">
              <h4>Market leader for over four decades</h4>
              <p>• Pioneer of organised recruitment in India</p>
              <p>• Unparalleled network and understanding of the Indian Market</p>
            </div>
          </div>
        </div>
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

.contain{
  width: 100%;
}
.all{
  background: url(https://images.unsplash.com/photo-1581299327801-faeb40ea459e?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=871&q=80);
  text-align: left;
  color: white;
  padding: 30px;
  width: 100%;
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
.flip-card {
  background-color: transparent;
  width: 300px;
  height: 200px;
  border: 1px solid #f1f1f1;
  perspective: 1000px; /* Remove this if you don't want the 3D effect */
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.cards{
  display: flex;
  padding: 20px;
  justify-content: space-around;
  flex-wrap: wrap;
}

.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden; /* Safari */
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: dodgerblue;
  color: white;
  padding: 30px;
}

.flip-card-back {
  background-color: dodgerblue;
  color: white;
  padding: 10px;
  text-align: left;
  transform: rotateY(180deg);
}

</style>

