<template>
<div>
  <div class="error">
        <h3>Error</h3>
        <p>Invalid Route</p>
        <NuxtLink to="/"><button>Home</button></NuxtLink>
        
      </div>
      <img :src="require(`@/assets/404.jpg`)" alt="">
</div>
  
</template>

<script>
export default {

}
</script>

<style scoped>
.error{
  background: url(https://images.unsplash.com/photo-1581299327801-faeb40ea459e?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=871&q=80);
  text-align: center;
  color: white;
  padding: 30px;
}

.error h3{
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

.view{
  background: rgb(158, 158, 0);
  height: 10px;
  width: 80px;
}
.error button{
    background-color: rgb(53, 53, 230);
    border: none;
    color: white;
    padding: 10px;
    border-radius: 5px;
}

img{
  width: 100%;
}

</style>