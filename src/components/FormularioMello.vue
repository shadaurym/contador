<template>
  <div>
    <h1>formulario</h1>
    
    <div> nombre <input v-model="info.nombre" type="text" ></div>
 <div>  apellido <input v-model="info.apellido" type="text" ></div>
    <div>   edad <input v-model="info.edad" type="number"></div>
   <div>telefono <input v-model="info.telefono" type="number" ></div>
    <div>trabajo <input v-model="info.trabajo" type="text"></div>
    <button @click="registrar()">enviar</button>
    
  </div  >
  
   <table class="table table-dark">
  <thead>
    <tr>
      
      <th scope="col">nombre</th>
      <th scope="col">apellido</th>
      <th scope="col">edad</th>
      <th scope="col">telefono</th>
      <th scope="col">trabajo</th>
     
    </tr>
  </thead>
   <tbody>
    <tr v-for="(datos,i) in tabladeDatos " :key="datos" >
      
       <td>{{datos.nombre}}</td>
      <td>{{datos.apellido}}</td>
      <td>{{datos.edad}}</td>
      <td>{{datos.telefono}}</td>
      <td>{{datos.trabajo}}</td>
      <td><button @click="elim(i)">delete</button></td>
      <td><button @click="edit()">edit</button></td>

    </tr>
  
  </tbody>
</table>
</template>

<script>


export default {
  name: 'Formulario',
  data() {
    return {
        tabladeDatos:[],
        info:{
        nombre:null,
        apellido:null,
        edad:null,
        telefono:null,
        trabajo:null,
        tabla:null
  
        
        }
        }
        
  },
  
  methods:{
   registrar(){
    let info = {...this.info}

    this.tabladeDatos.push(info)
    
   
   this.info.nombre=''
   this.info.apellido=''
   this.info.edad=''
   this.info.telefono=''
   this.info.trabajo=''
   console.log(this.tabladeDatos);
   },
  
   

    edit(i){
   let object={}
  object =  this.tabladeDatos[i]
 this.info.nombre=object.nombre
  this.info.apellido=object.apellido
   this.info.edad=object.edad
    this.info.telefono=object.telefono
     this.info.trabajo=object.trabajo


console.log(object);
    
    },
  
  elim(i){
   this.tabladeDatos.splice(i,1)

  }

  
   
  }
}
</script>

<style scoped>
 div{
    margin: 10px;

}
</style>