<template>
    <section>
        <div class="container">
            <div class="left">
                 <h2>
                    We Are Here To
                    Make Your <span class="green">Website</span>
                    Look More <span class="green">Elegant</span>
                    And Stylish!
                </h2>

                <div class="btn">
                    <a href="#">
                        VIEW ALL
                    </a>
                </div>
            </div>

            <div class="right">
                <div class="box">
                    <i class="fa-solid fa-gauge-simple-high"></i>
                    <h4>
                        Speed Optimization
                    </h4>
                    <p>
                        Far far away, behind the word mountains, far from the countries Vokalia Separeted...
                    </p>
                </div>
                <div class="box">
                    <i class="fa-solid fa-cloud"></i>
                    <h4>
                        Cloud Solutions
                    </h4>
                    <p>
                        Far far away, behind the word mountains, far from the countries Vokalia Separeted...
                    </p>
                </div>
                <div class="box">
                    <i class="fa-solid fa-tablet-screen-button"></i>
                    <h4>
                        Website Design
                    </h4>
                    <p>
                        Far far away, behind the word mountains, far from the countries Vokalia Separeted...
                    </p>
                </div>
                <div class="box">
                    <i class="fa-solid fa-stopwatch"></i>
                    <h4>
                        Online Marketing
                    </h4>
                    <p>
                        Far far away, behind the word mountains, far from the countries Vokalia Separeted...
                    </p>
                </div>
                <span class="side">17 years of experience helping people for best solutions</span>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'ProductPresentation'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';

section{
    padding: 120px 0;
    position: relative;

    .container{
        display: flex;
        justify-content: space-between;
        align-items: center;

        .left{
            width: 35%;
            h2{
                line-height: 60px;
                font-size: 40px;
                font-weight: 300;
                padding-right: 50px;

                .green{
                    color: $secondary_green;
                }
                &::after{
                    content: '';
                    width: 40px;
                    height: 3px;
                    margin: 20px 0;
                    background-color: $secondary_green;
                    display: block;
                }
            }

            .btn{
                background-color: $main_color_green;
                margin-top: 40px;
            }
        }

        .right{
            width: 65%;
            display: flex;
            flex-wrap: wrap;

            .box{
                width: calc(50% - 30px);
                margin: 15px;
                padding: 35px 25px;
                border-radius: 10px;
                background-color: $main_color_white;
                box-shadow: 0 0 18px 5px rgba(0, 0, 0, .1);

                i{
                    color: $main_color_green;
                    font-size: 30px;
                }

                h4{
                    padding: 25px 0;
                    font-weight: 300;
                    font-size: 20px;
                }
                
                p{
                    color: $text_grey;
                    font-size: 12px;
                }
            }

            .side{
                transform: rotate(270deg);
                position: absolute;
                font-size: 12px;
                top: 350px;
                right: -50px;
            }
        }
    }
}
</style>