<template>
<div>

 <!-- <Personas/> -->
 <FormularioMello/>
 <Contador/>
 
  
</div>
</template>

<script>


// import  Personas from  './components/Personas.vue'
  import FormularioMello from './components/FormularioMello.vue'
  import Contador from './components/Contador.vue'
export default {
  name: 'App',
  components: {
   
    // Personas
    FormularioMello,
    Contador
   
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
