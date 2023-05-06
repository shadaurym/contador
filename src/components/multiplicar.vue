<template>
  <div>
    <button class="button1" @click="multiplicar()"><h1>*</h1></button>

    <p>{{resultado}}</p>
  </div>
</template>

<script>
export default {
 data() {
    return {
        resultado:1
    }
 },

     methods: {
         multiplicar(){
            this.resultado= this.resultado*2
        }
    }
}
</script>

<style>

</style>