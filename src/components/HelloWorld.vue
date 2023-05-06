<template>
<div>
 



</div>
  <div v-for="persona in array" :key="persona">
    {{persona.nombre }}
    {{persona.edad}}
  </div>
  <div>
     <!-- <button @click="sumar()">+</button>
  <p>{{a}}</p>
     <button @click="restar()" >-</button> -->
  </div>

  
  <p>{{resultado}}</p>
  <p>{{mensaje}}</p>
  <div>
    <input v-model="numero1" type="number">
    <input v-model="numero2" type="number">
    
  </div>
    
    <div>
      <button @click="sumar()">+</button>
      <button @click="restar()">-</button>
      <button @click="multiplicar()" >*</button>
      <button @click="dividir()" >%</button>

    </div><br>


    <div>
      <input v-model="input1" type="text"><br><br>
      <input v-model="input2" type="text">
    </div>

    <button @click="enviar()" >enviar</button>
    <p> </p>
  
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      a:0,
      numero1:0,
      numero2:0,
      resultado:0,
      input1:null,
      input2:null,
      mensaje:null
    }
  },
  methods:{
    
    sumar(){
    this.resultado = this.numero1 + this.numero2
    
    },

   restar(){
    this.resultado = this.numero1 - this.numero2
    
   },

   multiplicar(){
    this.resultado = this.numero1 * this.numero2
   },

    dividir(){
      this.resultado = this.numero1 % this.numero2
    },

    enviar(){
     this.mensaje = `hola mi nombre es ${this.input1} y mi edad es ${this.input2}`
    }
  }
}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 img{
  width: 50px;
  height: 50px;
  
 }
 .p1{
 border-style:groove;
  box-shadow: 5px 5px 5px;
  margin: 10px 0px 20px ;
  
  
  width: 200px;
 }

 .divpadre{
  display: flex;
  justify-content: space-between;

  
 }
</style>
