<template>
    <div class="header-bottom">
        <div class="container">
            <div class="left">
                <img src="../assets/images/cropped-icon-32x32.png" alt="logo">
                Pholx | Business
            </div>
            <div class="center">
                <ul>
                    <ListItem v-for="item, index in headerLinks" :key="index" :list="item"/>
                </ul>
            </div>
            <div class="right">
                <div class="btn">
                    <a href="#">
                        PURCHASE
                    </a>
                </div>
                <div>
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import ListItem from './ListItem.vue'

export default {
    name: 'HeaderBottom',
    components: {
        ListItem
    },
    data(){
        return{
            headerLinks: [
                {
                    "item": 'HOME'
                },
                {
                    "item": 'ABOUT'
                },
                {
                    "item": 'SERVICES'
                },
                {
                    "item": 'SHOWCASE'
                },
                {
                    "item": 'BLOG'
                },
                {
                    "item": 'CONTACT'
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';
.container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;
    font-size: 11px;

    .left{
        display: flex;
        align-items: center;

        img{
            width: 40px;
            margin-right: 10px;
        }
    }

    .center ul{
        display: flex;
    }

    li{
        padding: 10px;
    }

    .right{
        display: flex;
        align-items: center;

        .btn{
            background-color: #00D9A6;
            color: $main_color_white;
            margin-right: 20px;
        }
    }
}
</style>