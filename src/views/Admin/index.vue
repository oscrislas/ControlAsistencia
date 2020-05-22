<template>
    <div>
        <lead></lead>
        <cuerpo></cuerpo>
        <sideBar></sideBar>
    </div>
</template>

<script>
import lead from '@/views/Admin/lead'
import cuerpo from '@/views/Admin/cuerpo'
import sideBar from '@/components/sideBar'

export default {
    name: 'Admin',
    components:{
        lead,
        cuerpo,
        sideBar
    }
}
</script>>