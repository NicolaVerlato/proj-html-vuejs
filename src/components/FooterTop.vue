<template>
    <section>
        <div class="container">

            <div class="card logo">
                <img src="../assets/images/cropped-Group-39-2x.png" alt="logo">
                <p class="text">
                    While the lovely valley teems with vapour around me, and the meridian sun strikes the upper surface of the impenetrable foliage of my trees. While the lovely valley teems with vapour around me.
                </p>
            </div>

            <div class="card links">
                <h3>QUICk LINKS</h3>

                <ul>
                    <FooterList v-for="item, index in FooterLinks" :key="index" :FooterItem="item"/>
                </ul>
            </div>

            <div class="card contact">
                <h3>CONTACT</h3>
                
                <div class="info">
                    <div class="text">
                        Patricia C. Amedee 4401 Waldeck Street Grapevive Nashville, TX 76051
                    </div>

                    <div class="text"> 
                        info@yourdomain.com
                    </div>

                    <div class="text">
                        +99 (0) 101 0000 888
                    </div>
                </div>
            </div>

            <div class="card map">
                <h3>LOCATION ON MAP</h3>

                <a href="#">
                    <img src="../assets/images/map.png" alt="map">
                </a>
            </div>
        </div>
    </section>
</template>

<script>
import FooterList from './FooterList.vue'
export default {
    name: 'FooterTop',
    components: {
        FooterList
    },
    data(){
        return{
            FooterLinks: [
                {
                    "item": 'Careers'
                },
                {
                    "item": 'News'
                },
                {
                    "item": 'Terms of use'
                },
                {
                    "item": 'Privacy Projects'
                },
                {
                    "item": 'About'
                },
                {
                    "item": 'Contact'
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';

section{
    padding: 100px 0;

    .container{
        display: flex;
        justify-content: space-between;

        h3::after{
                content: '';
                width: 40px;
                height: 3px;
                margin: 20px 0;
                background-color: $secondary_green;
                display: block;
            }

        .card{
            width: calc(25% - 15px);
        }

        .logo img{
            width: 180px;
        }

        .text{
            font-size: 12px;
            color: $text_grey;
            line-height: 18px;
            padding: 10px 0;
        }
    }
}
</style>