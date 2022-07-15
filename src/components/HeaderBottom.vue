<template>
    <div class="header-bottom">
        <div class="container">
            <div class="left">
                <img src="../assets/images/cropped-Group-39-2x.png" alt="logo">
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
.header-bottom{
    background-color: $main_color_white;
}
.container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;
    font-size: 11px;

    .left img{
            width: 140px;
            margin-right: 10px;
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
            margin-right: 20px;
        }

        i{
            color: #00D9A6;
        }
    }
}
</style>