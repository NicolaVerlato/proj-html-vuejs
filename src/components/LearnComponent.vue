<template>
    <section>
        <div class="images">
            <div class="image-green">
                <img src="../assets/images/busy-architect-PYVKWM4-1024x872.jpg" alt="architect">
            </div>
            <div class="img">
                <img src="../assets/images/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="businesswoman">
            </div>
        </div>

        <div class="text-area">
            <h2>learn more about our <span class="green">missions</span></h2>

            <p class="text">
                Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separeted they lived in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separeted they lived in Bookmarksgrove.
            </p>

            <div class="btn">
                <a href="#">
                    READ MORE
                </a>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'LearnComponent'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';

section{
    background-color: $background-color-grey;
    padding: 150px 0;
    position: relative;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .images{
        width: 65%;

        .image-green img{
            border-radius: 0 20px 20px 0;
            width: 600px;
        }
        .img{
            position: absolute;
            top: 200px;
            left: 200px;

            img{
                width: 600px;
                border-radius: 10px;
            }
        }
    }

    .text-area{
        width: 35%;
        padding: 0 50px;

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
        
        .btn{
            background-color: $main_color_green;
            margin-top: 20px;
        }
    }
}
</style>