<template>
    <div class="a">
        <lead></lead>
        <cuerpo></cuerpo>
 
    </div>
</template>

<script>
import lead from '@/views/Admin/lead'
import cuerpo from '@/views/Admin/cuerpo'


export default {
    name: 'Admin',
    components:{
        lead,
        cuerpo,
    
    }
}
</script>

<style  scoped>
.a{
    height: 800px;
}
</style>