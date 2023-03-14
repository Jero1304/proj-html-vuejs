<template>
    <div class="container">
        <div class="row py-4">
            <h3 class="col">Featured playlist</h3>
            <p class="col d-flex justify-content-end mb-0"> View all videos ></p>
        </div>
        <div class="row gap-4">
            <div class="card col">
                <div class="cover">
                    <p class="play">play</p>
                    <img src="../img/video2-2x.jpg" class="card-img-top" alt="...">
                </div>
                <div class="card-body">
                    <h3 class="card-title">Thighs & glute workout</h3>
                    <p class="card-subtitle">Increase your mobility</p>
                </div>
            </div>

            <div class="card col">
                <div class="cover">
                    <p class="play">play</p>
                    <img src="../img/video7-2x.jpg" class="card-img-top" alt="...">
                </div>
                <div class="card-body">
                    <h3 class="card-title">Lift, firm & perk up</h3>
                    <p class="card-subtitle">Feel young again</p>
                </div>
            </div>

            <div class="card col">
                <div class="cover">
                    <p class="play">play</p>
                    <img src="../img/video9-2x.jpg" class="card-img-top" alt="...">
                </div>
                <div class="card-body">
                    <h3 class="card-title">Slim & trim your waist</h3>
                    <p class="card-subtitle">Shed those exta pounds</p>
                </div>
            </div>

            
        </div>
    </div>
</template>

<script>

</script>

<style scoped lang="scss">
.container{
    padding-top: 140px;
    .card{
        width: 400px;
        border: none;
        position: relative;
        .cover{
            .play{
                color: white;
                position: absolute;
                top: 30%;
                right: 50%;
                transform: translate(50%,50%);
            }
            img{
                border-radius: 0 0 50px;
            }
        }
        .card-body{
            text-align: center;
            margin-top: 20px;
            .card-title{
                font-size: 22px;
            }
            .card-subtitle{
                font-size: 16px;
                color: blue;
            }
        }
    }
}
</style>