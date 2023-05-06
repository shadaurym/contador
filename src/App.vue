<template>
<div>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <Formulario/> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
 <!-- <Personas/> -->
 <!-- <Tarjetas/> -->
 <!-- <FormularioMello/> -->
 <Contador/>
 <!-- <Sumar/>
 <Restar/>
  <Multiplicar/> -->
  
</div>
</template>

<script>


// import HelloWorld from './components/HelloWorld.vue'
// import  Formulario from './components/Formulario.vue'
// import  Personas from  './components/Personas.vue'
  //  import Tarjetas from './components/Tarjetas.vue'
  // import FormularioMello from './components/FormularioMello.vue'
  import Contador from './components/Contador.vue'
    //  import Sumar from './components/sumar.vue'
    //  import Restar from './components/restar.vue'
    //  import Multiplicar from './components/multiplicar.vue'
export default {
  name: 'App',
  components: {
   
    // HelloWorld,
    // Formulario,
    // Personas
    // Tarjetas
    // FormularioMello
    Contador
    // Sumar,
    // Restar,
    // Multiplicar
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
</style>
