<template>
    <div class="header-top">
        <div class="container">
            <div class="left">
                <span>
                    <a href="#">
                        <i class="fa-solid fa-phone"></i> 
                    </a>
                </span>  
                <span>
                    <a href="#">
                        (001)88451234 
                    </a>
                </span> 
                <span>
                    <a href="#">
                        88455438 
                    </a>
                </span> 
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
    </div>
</template>

<script>
export default {
    name: 'HeaderTop'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';
.header-top{
    background-color: #555555;
    color: $main_color_white;
    padding: 5px 0;
    font-size: 10px;

    .container{
        display: flex;
        justify-content: space-between;
    }

    .left a{
        padding: 2px;
    }

    .right a{
        padding: 0 5px;
    }
}
</style>