<template>
  <div id="jumbo">
    <h1 class="fw-bold">IL MIO JUMBO VUE</h1>
    <p>comincia il tuo viaggio</p>
    <button class="btn btn-lg btn-success mt-3">INIZIA</button>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  #jumbo{
    background-image: url("https://wallpapercave.com/wp/wp7487214.jpg");
    width: 100%;
    height: 500px;
    background-size: cover;
  }

  h1{
    font-size: 60px;
    padding: 30px;
    padding-bottom: 0;
    margin: 0 auto;
  }

  p{
    font-size: 20px;
    margin-top: 0;
    margin-bottom: 10px;
  }

</style>