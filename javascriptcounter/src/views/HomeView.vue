<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
  </div>
  <div class="counter">
    0
  </div>
  <div class="button">
    <button>-</button>
    <button>+</button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  }

</script>

<style>
  div{
    margin-bottom: 10px;
  }
  .counter{
    font-size: 80px;
  }
  .button button{
    font-size: 40px;
    width: 100px;
    margin: 0 10px;
  }
</style>
