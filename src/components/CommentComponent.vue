<template>
    <section>
        <div class="container">
            <div class="icon green">
                <i class="fa-solid fa-quote-left"></i>
            </div>

            <p>
                When it comes to barbequing, there are two main schools of thought for the techniques thet you can use. Freshly scrambled eggs with applewood smoked bacon - are amazing!
            </p>

            <div class="person">
                <div class="img">
                    <img src="../assets/images/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="businnes woman">
                </div>
                <div class="green">
                    LISSA DURBIN
                </div>
                <div class="small">
                    Client
                </div>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name: 'CommentComponent'
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/colors';

section{
    padding: 100px 0;
    background-image: url(../assets/images/four-businesspeople-in-a-boardroom-with-paperwork-PC4V8H4.jpg);
    background-color: #444444;
    background-size: cover;
    background-position: center;
    background-blend-mode: multiply;
    
    .container{
        width: 60%;
        text-align: center;
        color: $main_color_white;

        .icon{
            margin-bottom: 30px;

            i{
                font-size: 30px;
            }
        }

        p{
            font-style: italic;
            font-size: 18px;
            margin-bottom: 50px;
        }

        .person{
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;

            .img{
                height: 70px;
                width: 70px;
                margin-bottom: 20px;

                img{
                   height: 100%;
                   border-radius: 50%;
                   object-fit: cover;
                   border: 1px solid white;
                }
            }

            .small{
                font-size: 13px;
                margin-top: 5px;
                font-weight: 700;
            }
        }
    }
}
</style>