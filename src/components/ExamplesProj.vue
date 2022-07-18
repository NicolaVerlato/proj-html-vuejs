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
            <img src="../assets/images/ina-soulis-227104-unsplash-1024x1024.jpg" alt="flowers">
            <img src="../assets/images/sunisa-misa-531163-unsplash-1024x1024.jpg" alt="ferris wheel">
            <img src="../assets/images/355H-1024x1024.jpg" alt="shoes">
            <img src="../assets/images/photo-1448932252197-d19750584e56-1024x1024.jpg" alt="man">
            <img src="../assets/images/business-competition-PB366D8-1024x1024.jpg" alt="origami">
            <img src="../assets/images/cozy-sofa-in-living-room-PQR5AB9-1024x1024.jpg" alt="sofa">
            <img src="../assets/images/aa9a4539-PQGJ7HU-1024x1024.jpg" alt="hot air baloon">
            <img src="../assets/images/cody-davis-253928-unsplash-1024x1024.jpg" alt="orange">
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

        img{
            width: calc(25% - 8px);
            margin: 4px;
            border-radius: 5px;
        }
    }

    .btn{
        background-color: $main_color_green;
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