<template>
    <div class="bg-service">
        <div class="container">
            <div class="row">
                <div class="card">
                    <img src="../img/service6-2x.jpg" class="card-img" alt="...">
                    <div class="card-img-overlay">
                        <p>/\/\/\</p>
                        <h2 class="card-title">Crossfit Workout</h2>
                        <h3 class="card-text">Push your limits</h3>
                    </div>
                </div>

                <div class="card">
                    <img src="../img/service6-2x.jpg" class="card-img" alt="...">
                    <div class="card-img-overlay">
                        <p>/\/\/\</p>
                        <h2 class="card-title">Crossfit Workout</h2>
                        <h3 class="card-text">Push your limits</h3>
                    </div>
                </div>

                <div class="card">
                    <img src="../img/service6-2x.jpg" class="card-img" alt="...">
                    <div class="card-img-overlay">
                        <p>/\/\/\</p>
                        <h2 class="card-title">Crossfit Workout</h2>
                        <h3 class="card-text">Push your limits</h3>
                    </div>
                </div>     
            </div>
            <div class="container citation">
                <h1 class="text-citation">
                    “How you respond to the service in the second half will determine what you become after the game, whether you are a winner or a loser.”
                </h1>
                <p class="text-white fs-2 py-2">/\/\/\</p>
                <div class="person-citation">
                    <img class="profile-citation" src="../img/avatar-1-2x.jpg" alt="">
                    <h3 class="name-citation fw-bold">Brad Johnson</h3>
                    <h3 class="city-citation">Las Vegas</h3>
                </div>



            </div>
        </div>

    </div>
</template>

<script>
</script>

<style lang="scss" scoped>
.bg-service{
    background: rgb(14,0,255);
    background: linear-gradient(135deg, rgba(14,0,255,1) 0%, rgba(141,0,150,1) 50%, rgba(255,0,0,1) 100%);
    padding: 0 120px 150px;
    .card{
        background: none;
        width: 400px;
        padding: 0;
        margin: 0 20px 30px;
        border: none;
        img{
            border-radius: 0 0 50px;
        }
        .card-img-overlay{
            position: absolute;
            bottom: 0;
            top:auto;
            color: white;
        }
    }

    .citation{
        text-align: center;
        .text-citation{
            color: white;
            padding: 0 150px;
        }
        .person-citation{
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 14px;
            .profile-citation{
                width: 70px;
                border-radius: 999px;
            }
            h3{
                color: white;
                font-size: 22px;
            }
            
        }
    }
}

</style>