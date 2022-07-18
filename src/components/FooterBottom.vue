<template>
    <section>
        <div class="container">
            <div class="left">
                <i class="fa-regular fa-copyright"></i>
                <span> 2020 PHLOX BUSINESS THEME.</span>
            </div>

            <div class="right">
                <a href="#">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a href="#">
                    <i class="fa-brands fa-twitter"></i>
                </a>
                <a href="#">
                    <i class="fa-brands fa-pinterest-p"></i>
                </a>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'FooterBottom'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';

section{
    background-color: #555555;
    padding: 30px 0;
    color: $main_color_white;
    font-size: 11px;

    .container{
        display: flex;
        justify-content: space-between;

        .right a{
            padding: 0 8px;
        }
    }
}
</style>