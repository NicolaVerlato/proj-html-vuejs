<template>
    <section>
        <div class="container">
            <div class="text-area">
                <div class="title">
                    <h2>
                        With <span class="green">Live Chat 24/7</span> Support
                    </h2>
                </div>
                <p class="text">
                    Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separeted they lived in Bookmarksgrove right at the coast of the Semantics.
                </p>
            </div>

            <div class="card">
                <div class="price">
                    <div class="info">
                        <h4>
                            DESIGNING
                        </h4>
                        <div class="text">
                            All Design
                        </div>
                    </div>

                    <div class="white">
                        $ <span>13</span> /Design
                    </div>
                </div>

                <ul>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Creative Design Enabled
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Vibrant Color Usage
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Eye Catching Design
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Extreme Typography
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Exeptional Design
                    </li>
                </ul>
            </div>

            <div class="card">
                <div class="price no-black">
                    <div class="info">
                        <h4>
                            DEVELOPMENT
                        </h4>
                        <div class="text">
                            WordPress Projects
                        </div>
                    </div>

                    <div class="white">
                        $ <span>15</span> /Project
                    </div>
                </div>

                <ul>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Creative Design Enabled
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Vibrant Color Usage
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Eye Catching Design
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Extreme Typography
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Exeptional Design
                    </li>
                </ul>
            </div>

            <div class="card">
                <div class="price">
                    <div class="info">
                        <h4>
                            SEO
                        </h4>
                        <div class="text">
                            Web Products
                        </div>
                    </div>

                    <div class="white">
                        $ <span>10</span> /Product
                    </div>
                </div>

                <ul>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Creative Design Enabled
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Vibrant Color Usage
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Eye Catching Design
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Extreme Typography
                    </li>
                    <li>
                        <span><i class="fa-solid fa-check"></i></span> Exeptional Design
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'ProductPrices'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';

section{
    padding: 100px 0;
    background-color: $background-color-grey;

    .container{
        display: flex;
        align-items: center;

        .text-area{
            width: 30%;
            padding-right: 30px;

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
        }

        .card{
            border-radius: 10px;
            text-align: center;
            background-color: $main_color_white;
            box-shadow: 0 0 18px 5px rgba(0, 0, 0, .1);
            width: calc((70% / 3) - 30px);
            margin: 0px 15px;

            .price{
                background-color: $main_color_black;
                background-image: linear-gradient(to right, #555555, $main_color_black);
                padding: 1px 0;
                border-radius: 10px 10px 0 0;

                .white{
                    color: $main_color_white;
                    padding: 20px 0;

                    span{
                        font-size: 30px;
                        margin: 0 5px;
                        vertical-align: sub;
                    }
                }
                
                .info{
                    background-color: $main_color_white;
                    padding: 10px 0;
                    margin-top: 10px;
                }
            }

            .no-black{
                background-image: linear-gradient(to right, lightgreen, $main_color_green);
            }
        }

        .text{
            font-size: 11px;
            color: $text_grey;
            line-height: 18px;
            padding: 3px 0;
        }

        ul{
            padding: 30px 0;

            li{
                padding: 10px 0;
                font-size: 11px;
                color: $text_grey;

                span{
                    color: black;
                    margin-right: 10px;
                }
            }
        }
    }
}
</style>