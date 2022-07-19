<template>
    <section class="container">
        <div class="text-area">
            <div class="title">
                <h2>
                    Our recent <span class="green">web design</span> & some examples of past <span class="green">projects</span>
                </h2>
            </div>
            <p class="text">
                Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separeted they lived in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separeted they lived in Bookmarksgrove.
            </p>
        </div>

        <div class="images">
            <div class="img">
                <img src="../assets/images/ina-soulis-227104-unsplash-1024x1024.jpg" alt="flowers">

                <div class="img-text">
                    Flowers
                </div>
            </div>
            <div class="img">
                <img src="../assets/images/sunisa-misa-531163-unsplash-1024x1024.jpg" alt="ferris wheel">

                <div class="img-text">
                    Ferris wheel
                </div>
            </div>
            <div class="img">
                <img src="../assets/images/355H-1024x1024.jpg" alt="shoes">

                <div class="img-text">
                    Shoes
                </div>
            </div>
            <div class="img">
                <img src="../assets/images/photo-1448932252197-d19750584e56-1024x1024.jpg" alt="man">

                <div class="img-text">
                    Man
                </div>
            </div>
            <div class="img">
                <img src="../assets/images/business-competition-PB366D8-1024x1024.jpg" alt="origami">

                <div class="img-text">
                    Origami
                </div>
            </div>
            <div class="img">
                <img src="../assets/images/cozy-sofa-in-living-room-PQR5AB9-1024x1024.jpg" alt="sofa">

                <div class="img-text">
                    Sofa
                </div>
            </div>
            <div class="img">
                <img src="../assets/images/aa9a4539-PQGJ7HU-1024x1024.jpg" alt="hot air baloon">

                <div class="img-text">
                    Hot Air Baloon
                </div>
            </div>
            <div class="img">
                <img src="../assets/images/cody-davis-253928-unsplash-1024x1024.jpg" alt="orange">

                <div class="img-text">
                    Orange
                </div>
            </div>
        </div>

        <div class="btn">
            <a href="#">
                READ MORE
            </a>
        </div>

        <span class="side">17 years of experience helping people for best solutions</span>
    </section>
</template>

<script>
export default {
    name: 'ExamplesProj'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';

section{
    padding: 100px 0;
    position: relative;

    .text-area{
        display: flex;
        align-items: flex-end;
        margin-bottom: 50px;

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

            &::before{
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
    }

    .images{
        display: flex;
        flex-wrap: wrap;

        .img{
            width: calc(25% - 8px);
            margin: 4px;
            position: relative;

            .img-text{
                display: none;
                position: absolute;
                bottom: 25px;
                left: 15px;
                width: 100%;
            }

            img{
                border-radius: 5px;
            }

            &:hover{
                transform: scale(1.1);
                transition-duration: 0.5s;
                z-index: 2;
                cursor: pointer;
                
                img{
                    background-image: linear-gradient(to right, lightgreen, $main_color_green);
                    filter: brightness(50%);
                }

                .img-text{
                    display: block;
                    color: white;
                }
            }
        }
    }

    .btn{
        background-color: $main_color_green;
        background-image: linear-gradient(to right, lightgreen, $main_color_green);
        box-shadow: 0 0 18px 5px rgba(0, 0, 0, .1);
        margin: 70px auto;
    }

    .side{
        transform: rotate(270deg);
        position: absolute;
        font-size: 12px;
        top: 700px;
        right: -170px;
    }
}

</style>