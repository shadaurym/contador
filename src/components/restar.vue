<template>
<div>
    <button class="button1" @click="restar()"><h1>-</h1></button>
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
         methods:{
             restar(){
            this.resultado--
        }
        }

}
</script>

<style>

</style>