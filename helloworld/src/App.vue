<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h4 class="promoted" >{{name}}</h4>

  
</template>

<script>


export default {
  name: 'App',
  data(){
     return{
       name: "isaac",
       movie: "spiderman",
       ispromoted:true
     }
  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.soldout{
 color:"red"
}
.promoted{
  color:"green"
}
</style>
