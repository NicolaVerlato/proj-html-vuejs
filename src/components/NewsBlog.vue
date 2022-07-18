<template>
    <section>
        <div class="container">
            <h2>
                Latest News & Our <span class="green">Blog</span>
            </h2>

            <div class="card-container">
                <div class="card">
                    <img src="../assets/images/serious-businesswoman-with-documents-talking-on-P9Q6LX6-1024.jpg" alt="Businesswoman">
                    <div class="banner">
                        <div class="text">
                            May 24, 2018 .by Alex
                        </div>

                        <h4>Marketing Ideas</h4>
                    </div>
                </div>

                <div class="card">
                    <img src="../assets/images/Businessman-at-the-desk-in-his-office-resting--1024x768.jpg" alt="Businessman">
                    <div class="banner">
                        <div class="text">
                            May 24, 2018 .by Alex
                        </div>

                        <h4>Rest During Working Hours</h4>
                    </div>
                </div>

                <div class="card">
                    <img src="../assets/images/simple-home-office-with-tree-PBXRXYB-large-1024x768.jpg" alt="office">
                    <div class="banner">
                        <div class="text">
                            May 24, 2018 .by Alex
                        </div>

                        <h4>Develop Your Start Idea</h4>
                    </div>
                </div>
            </div>

            <span class="side">17 years of experience helping people for best solutions</span>

            <div class="btn">
                <a href="#">
                    VIEW ALL POST
                </a>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'NewsBlog'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';

section{
    text-align: center;
    padding: 100px 0;
    position: relative;

    h2{
        line-height: 60px;
        font-size: 40px;
        font-weight: 300;
        padding-right: 50px;

        &::after{
            content: '';
            width: 40px;
            height: 3px;
            margin: 25px auto;
            background-color: $secondary_green;
            display: block;
        }

    }

    .card-container{
        display: flex;

        .card{
            width: 32%;
            margin: 0 auto;
            position: relative;

            img{
                border-radius: 10px;
                box-shadow: 0 0 18px 5px rgba(0, 0, 0, .1);
            }

            .banner{
                width: 300px;
                position: absolute;
                background-color: $main_color_white;
                box-shadow: 0 0 18px 5px rgba(0, 0, 0, .1);
                bottom: -40px;
                left: 50px;
                padding: 20px 30px;
                border-radius: 10px;
                text-align: left;
            }
        }
    }

    .btn{
        background-color: $main_color_black;
        background-image: linear-gradient(to right, #555555, $main_color_black);
        box-shadow: 0 0 18px 5px rgba(0, 0, 0, .1);
        width: 170px;
        margin-top: 100px;
        margin: 100px auto;
    }

    .side{
        transform: rotate(270deg);
        position: absolute;
        font-size: 12px;
        top: 370px;
        left: -70px;
    }

    .text{
        font-size: 11px;
        color: $text_grey;
        padding: 10px 0;
    }
}
</style>