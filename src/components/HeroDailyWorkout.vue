<template>
    <div class="bg-hero">
        <div class="container">
            <div class="row align-items-center justify-content-center">
                <div class="col-8">
                    <p class="play">play</p>
                    <h2 class="title">Crossfit workout of the day</h2>
                    <p class="date">November 15th, 2019</p>
                    <a class="link" href="">
                        View all videos
                        <span class="px-2">
                           <font-awesome-icon icon="fa-solid fa-arrow-right" />
                        </span>
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style scoped lang="scss">
.bg-hero{
    background-image:linear-gradient(90deg, rgba(8, 0, 160, 0.7) 0%, rgba(255,0,219,0.3) 100%), url('../img/banner14-2x.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    padding-bottom: 200px;
    color: white;
    margin-top: 100px;
    text-align: center;
    .container{
        padding-top: 300px;
        .play{
            font-size: 40px;
        }
        .title{
            font-size: 54px;
            padding: 10px 0;
        }
        .date{
            color: yellow;
            font-size: 36px;
            margin-bottom: 0;

        }
        .link{
            text-decoration: none;
            color: currentColor;
            font-size: 20px;
        }
    }
}

</style>