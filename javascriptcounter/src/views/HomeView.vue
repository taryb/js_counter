<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
  </div>
  <div class="counter">
    {{ counter }}
  </div>
  <div class="button">
    <button @click="decreaseCount">-</button>
    <button @click="increaseCount">+</button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  data(){
    return{
      counter: 0
    }
  },
  methods:{
    increaseCount(){
      this.counter++;
    },
    decreaseCount(){
      this.counter--;
    }

  }
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
