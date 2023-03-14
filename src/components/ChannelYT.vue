<template>
    <div class="channel-yt">
        <div class="row">
            <div class="col video-yt">
                <h1 class="text-white">play</h1>
            </div>
            <div class="col container text">
                <p class="sub-title">Tune up your workouts</p>
                <h1 class="title">The best health & fiteness advice online</h1>
                <p class="info">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil placeat tenetur possimus sunt totam ab?</p>
                <button type="button" class="btn btn-danger">Visit my YouTube channel</button>
            </div>
        </div>
    </div>
    
</template>

<script>

</script>

<style scoped lang="scss">
    .video-yt{
        margin-top: -60px;
        background-image: url('../img/service15-2x.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        height: 900px;
        width: 1000px;
        border-radius: 0 0 50px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .container{
        padding: 120px 100px;
    }
    .text{
        display: flex;
        align-items: start;
        justify-content: center;
        flex-direction: column;
        .sub-title{
            color: blue;
            font-size: 26px;
        }
        .title{
            font-size: 60px;
        }
        .info{
            padding-top:20px ;
            font-size: 24px;
            color: grey;
        }
        .btn{
            padding: 15px 35px;
            border-radius: 30px;
            font-weight: bold;
            color: white;
            margin-top: 30px;
        }
    }
            
</style>    