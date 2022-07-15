<template>
    <div>
        <HeaderTop />
        <HeaderBottom />
    </div>
</template>

<script>
import HeaderTop from './HeaderTop.vue'
import HeaderBottom from './HeaderBottom.vue'

export default {
    name: 'HeaderComponent',
    components:{
        HeaderTop,
        HeaderBottom
    }
}
</script>

<style lang="scss" scoped>

</style>