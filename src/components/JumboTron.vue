<template>
    <section>
        <div class="container">
            <div class="left">
                <div class="pre-title">
                    17 YEARS OF EXPERIENCE
                </div>
                <h1>
                    Focus on Your 
                    <div class="green">Business</div>    
                </h1>
                <p class="text">
                    Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separeted they lived in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separeted they lived in Bookmarksgrove.
                </p>

                <div class="btn">
                    <a href="#">
                        READ MORE
                    </a>
                </div>

                <div class="flex">
                    <div class="socials">
                        <span>
                            <a href="#">
                                FACEBOOK -
                            </a>
                        </span>
                        <span>
                            <a href="#">
                                INSTAGRAM -
                            </a>
                        </span>
                        <span>
                            <a href="#">
                                YOUTUBE -
                            </a>
                        </span>
                        <span>
                            <a href="#">
                                TWITTER
                            </a>
                        </span>
                    </div>

                    <div class="banner">
                        <span>01</span> <span class="no-black">02</span> <span>03</span>
                    </div>
                </div>
            </div>

            <div class="right">
                <img src="../assets/images/Group-35-2x.png" alt="jumbotron image">
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'JumboTron'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';
section{
    background-color: $background-color-grey;
    overflow: hidden;
}
.container{
    display: flex;
    align-items: center;
    position: relative;
    background-color: $background-color-grey;

    .left{
        width: 40%;
        padding-top: 90px;
        padding-bottom: 50px;

        .pre-title{
            padding-bottom: 20px;
            color: $secondary_green;
            font-size: 13px;
        }

        h1{
            font-size: 50px;

            &::after{
                content: '';
                width: 40px;
                height: 3px;
                background-color: $secondary_green;
                display: inline-block;
            }
        }

        .text{
            font-size: 12px;
            color: $text_grey;
            line-height: 18px;
            padding: 40px 0;
        }
        .btn{
            background-color: $btn_black;
            background-image: linear-gradient(to right, #555555, $main_color_black);
            box-shadow: 0 0 18px 5px rgba(0, 0, 0, .1);
        }
        .flex{
            display: flex;
            align-items: flex-end;
            justify-content: space-between;
        }
        .socials{
            font-size: 12px;
            padding-top: 70px;
        }
        .banner{
            background-image: linear-gradient(to right, #555555, #000000);
            width: 150px;
            height: 38px;
            color: #888888;
            border-radius: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 18px;

            .no-black{
                background-image: linear-gradient(to right, lightgreen, $main_color_green);
                border-radius: 15px;
                text-align: center;
                width: 50px;
                height: 85%;
                line-height: 32px;
            }
        }
    }

    img{
        position: absolute;
        top: -170px;
        right: -400px;
    }
}

</style>