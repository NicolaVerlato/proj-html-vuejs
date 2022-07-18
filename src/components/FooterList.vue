<template>
    <div>
        <li class="text">
            <a href="#">
                {{ FooterItem.item }}
            </a>
        </li>
    </div>
</template>

<script>
export default {
    name: 'FooterList',
    props:{
        FooterItem: Object
    }
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/common';
@import '../assets/styles/colors';

li{
    text-align: center;
    padding: 3px 0;
}
.text{
    font-size: 12px;
    color: $text_grey;
    line-height: 18px;
}
</style>