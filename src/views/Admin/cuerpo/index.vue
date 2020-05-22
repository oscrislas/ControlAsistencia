<template>
    <div class="container my-5">
       <div class="row">
            <div class="col-6">
                <checador></checador>
            </div>
            <div class="col-6">
                <izquierda></izquierda>
                <calendario></calendario>
            </div>
       </div>

    </div>
</template>

<script>
import izquierda from './izquierda.vue'
import checador from '@/components/checador'
import calendario from '@/components/calendario'
export default {
    name: 'cuerpo',
    components:{
        izquierda,
        checador,
        calendario
    },
    methods:{
        cambia(){
            console.log(this.$data.nombre)
        }
    }
}
</script>>