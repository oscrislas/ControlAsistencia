<template>
    <div>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corrupti explicabo deleniti, illo asperiores omnis molestias dignissimos atque iste maxime minima totam libero rerum! Non corporis incidunt qui voluptatibus quas reprehenderit.
    <b-button v-on:click="cambia" >press</b-button>
    </div>
</template>

<script>

export default {
    name: 'cuerpo',
    methods:{
        cambia(){
            console.log(this.$data.nombre)
        }
    }
}
</script>>