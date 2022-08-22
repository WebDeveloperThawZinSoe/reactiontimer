<template>
  <h1 id="title">How Fast Can You Catch Me ? </h1>
  <button id="btn" @click="start">Play</button>
</template>

<script>
export default{
  name : "App",
  components:{
    
  },
  data(){
    return{
          isPlaying : false
    }
  },
  methods:{
    start(){
      this.isPlaying = true;
    }
  }
}
</script>

<style>
  #title{
    text-align: center;
    padding-top: 20px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  #btn{
    margin-left: 45% !important;
    display: inline-block;
    background-color: black;
    color: white;
    padding: 10px 40px;
    border-radius: 5px;
  }
  #btn:hover{
    background-color:gray ;
  }
</style>
