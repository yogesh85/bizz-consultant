<template>
  <div class="contact">
      <br><br>
      <div class="contact_us">
        <div class="add">
        <div>
          <h4>Corporate Office</h4>
          <br>
          <h5>Delhi</h5>
          <h6>1st Floor, Eros Corporate Tower</h6>
          <h6>Nehru Place</h6>
          <h6>New Delhi 110 019</h6>
          <br>

          <h6>T: +91 11 4934 3900</h6>
          <h6>E: info@abcconsultants.in</h6>
        </div>
        
        <br>
        <br>
        <div>
         <h4>Main Office</h4>
         <br>
        <h5>Bengaluru</h5>
        <h6>1st Floor, Eros Corporate Tower</h6>
        <h6>Benargatta</h6>
        <h6>Bengaluru</h6> 
        <br>
        <h6>T: +91 11 4934 3900</h6>
          <h6>E: info@abcconsultants.in</h6>
        </div>
        
      </div>
      <div class="map">
        <Map />
      </div>
      </div>
      
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.contact_us{
  
  display: flex;
  flex-direction: row;
}
.add{
  text-align: center;
  padding: 15px;
  display: flex;
  width: 100%;
  justify-content: space-evenly;
  flex-direction: row;
}
.contact{
   text-align: center;
  padding: 10px;

  background: white;
  margin-bottom: 0px;
}
.map{
  width: 100%;
}
.add h4{
  font-style: oblique;
}
.contact h2{
  font-size: 40px;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
</style>