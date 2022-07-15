<template>
    <li>
        <a href="#">
            {{ list.item }}
        </a>
    </li>
</template>

<script>
export default {
    name: 'ListItem',
    props:{
        list: Object
    }
}
</script>

<style lang="scss" scoped>

</style>