<template>

<div class="container">

    <h1 class="titulo">contador</h1><br>

  <button class="button1"  @click="sumar()"><h1>+</h1></button><br><br>

  <button class="button1" @click="restar()"><h1>-</h1></button><br><br>

  


 
  
<div>
    <h1>{{resultado}}</h1>
</div>

   </div>
</template>

<script>
export default {
   data() {
    return {
        resultado:0
    }
   },
    methods: {
        sumar(){
            this.resultado++

        },

        restar(){
            this.resultado--
        },

      
    },

}
</script>

<style scoped>
.titulo{
  box-shadow: 5px 5px 5px 5px black;
  
}

button{

    width: 70px;
     
}

.button1:hover{

color: red;

}

.container{
  width: 500px;
  border: solid brown;
}
</style>