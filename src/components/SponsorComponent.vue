<template>
    <section>
        <div class="container">
            <div class="banners">
                <div class="start">
                    <div class="text">
                        Are You Ready?
                    </div>
                    <h2>Start a New Project</h2>

                    <div class="input">
                        <input type="text" placeholder="Enter Your Email Address">
                        <button>SUBMIT</button>
                    </div>
                </div>

                <div class="about">
                    <div class="text">
                        What Are You Waiting for?
                    </div>
                    <h2>Let's Talk About Work</h2>

                    <div class="btn">
                        START NOW
                    </div>
                </div>
            </div>

            <div class="images">
                <img src="../assets/images/client-1-2x.png" alt="client">
                <img src="../assets/images/client-9-2x.png" alt="client">
                <img src="../assets/images/client-7-2x.png" alt="client">
                <img src="../assets/images/client-3-2x.png" alt="client">
                <img src="../assets/images/client-4-2x.png" alt="client">
                <img src="../assets/images/client-5-2x.png" alt="client">
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SponsorComponent'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';

section{
    background-color: $background-color-grey;
    position: relative;

    .banners{
        width: 80%;
        display: flex;
        justify-content: space-between;
        text-align: center;
        position: absolute;
        top: -130px;
        left: 150px;

        h2{
            margin-bottom: 40px;
        }

        .start{
            background-color: $main_color_black;
            color: $main_color_white;
            width: 49%;
            border-radius: 10px;
            padding: 40px 0;

            .input{
                input{
                    width: 220px;
                    padding: 15px 25px;
                    border-radius: 20px 0 0 20px;
                    font-size: 13px;
                    border: 0;
                    background-color: rgba($color: #888888, $alpha: 0.5);
                    color: white;
                }

                button{
                    width: 90px;
                    padding: 15px 0;
                    font-size: 13px;
                    color: $text_grey;
                    font-weight: 700;
                    border-radius: 0 20px 20px 0;
                    border: 0;
                    background-color: rgba($color: #888888, $alpha: 0.5);
                }
            }
        }

        .about{
            background-color: $main_color_green;
            color: $main_color_white;
            width: 49%;
            border-radius: 10px;
            padding: 40px 0;

            .btn{
                margin: auto;
                background-color: $main_color_black;
            }
        }
    }

    .images{
        display: flex;
        justify-content: space-between;
        padding-top: 190px;
        padding-bottom: 100px;

        img{
            width: 90px;
            margin: auto;
        }
    }

    .text{
        font-size: 12px;
        color: $text_grey;
        line-height: 18px;
        padding: 10px 0;
    }
}
</style>