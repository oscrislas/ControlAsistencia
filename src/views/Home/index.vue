<template>
    <div>
        <lead></lead>
        <cuerpo></cuerpo>
        <foot></foot>
    </div>
</template>

<script>
import lead from '@/views/Home/header'
import cuerpo from '@/views/Home/home'
import foot from '@/views/Home/fotter'
export default {
    name: 'home',
    components:{
        lead,
        cuerpo,
        foot

    }
}
</script>>