<template>
<div>
  <button class="button1"  @click="sumar()"><h1>+</h1></button>
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
        sumar(){
            this.resultado++

        },
}
}
</script>

<style>

</style>