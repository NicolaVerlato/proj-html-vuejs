<template>
    <section>
        <div class="img-green">
            <div class="top">
                <div class="number">
                    280
                </div>
                <div class="text">
                    PROJECTS
                </div>
            </div>

            <div class="bottom">
                <div class="left">
                    <div class="number">
                        +3,500
                    </div>
                    <div class="text">
                        USERS COMMENTS
                    </div>
                </div>

                <div class="right">
                    <div class="number">
                        100%
                    </div>
                    <div class="text">
                        HAPPY CLIENTS
                    </div>
                </div>
            </div>
        </div>

        <div class="aside">
            <h2>
                What <span class="green">Love</span> What <br> We Do
            </h2>

            <div class="text">
                Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separeted they lived in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separeted they lived in Bookmarksgrove. Far far away, behind the word mountains, far from the countries Vokalia and Consonantia.
            </div>

            <ul class="text">
                <li>
                    <span class="green"><i class="fa-solid fa-check"></i></span> far far away, behind the word mountains
                </li>
                <li>
                    <span class="green"><i class="fa-solid fa-check"></i></span> large language ocean
                </li>
                <li>
                    <span class="green"><i class="fa-solid fa-check"></i></span> far from the countries Vokalia and Consonantia
                </li>
            </ul>
        </div>

    </section>
</template>

<script>
export default {
    name: 'WhatWeDo'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';

section{
    background-color: $background-color-grey;
    padding: 100px 0;
    position: relative;

    .img-green{
        width: 600px;
        height: 500px;
        background-image: url(../assets/images/person-with-long-curly-hair-PZ99QM2-2x.jpg);
        background-size: cover;
        border-radius: 10px;
        display: flex;
        align-items: center;
        flex-direction: column;
        justify-content: center;
        color: $main_color_white;
        margin-left: 100px;

        .top{
            text-align: center;
            margin-bottom: 20px;

            .number{
                font-size: 80px;
                margin-bottom: 10px;
            }
            .text{
                font-size: 13px;
            }
        }

        .bottom{
            display: flex;
            text-align: center;
            margin-bottom: 10px;

            .left{
                margin-right: 60px;
            }

            .number{
                font-size: 30px;
                margin-bottom: 8px;
            }
            .text{
                font-size: 13px;
            }
        }
    }

    .aside{
        width: 600px;
        height: 500px;
        background-color: $main_color_white;
        padding: 70px 50px;
        position: absolute;
        top: 150px;
        right: 200px;
        border-radius: 10px;

        h2{
            line-height: 60px;
            font-size: 40px;
            font-weight: 300;
            padding-right: 50px;

            &::after{
                content: '';
                width: 40px;
                height: 3px;
                margin: 20px 0;
                background-color: $secondary_green;
                display: block;
            }

        }

        .text{
            font-size: 12px;
            color: $text_grey;
            line-height: 18px;
            padding: 10px 0;
        }

        .green{
            margin-right: 5px;
        }
    }
}
</style>