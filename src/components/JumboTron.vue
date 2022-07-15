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
        width: 35%;
        padding-top: 90px;
        padding-bottom: 50px;

        .pre-title{
            padding-bottom: 20px;
            color: $secondary_green;
            font-size: 13px;
        }

        h1{
            font-size: 50px;

            .green{
                color: $secondary_green;
            }

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
        }
        .socials{
            font-size: 12px;
            padding-top: 70px;
        }
    }

    img{
        position: absolute;
        top: -170px;
        right: -400px;
    }
}

</style>