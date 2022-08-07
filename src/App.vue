<template>
  <div id="app">
    <Home class="card_vue home_vue"/>
    <Estoque class="card_vue home_vue2"/>
    <Relatorios class="card_vue home_vue3"/>
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Estoque from './components/Estoque.vue'
import Relatorios from './components/Relatorios.vue'
export default {
  name: 'App',
  components: {
    Home,Estoque,Relatorios
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
}
.card_vue{
  border: 1px solid red;
  border-radius: 15px;
  height: 50%;
  width: 20%;
 
}
.home_vue{
  width: 30%;
  align-content: center;
  position: fixed;
  margin-left: 2%;
}
.home_vue2{
  width: 30%;
  align-content: center;
  position: fixed;
  margin-left:33%;
}
.home_vue3{
  width: 30%;
  align-content: center;
  position: fixed;
  margin-left:64%;
}
</style>
