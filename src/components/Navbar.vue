<template>
    <nav class="navbar navbar-expand-lg">
        <div class="container">
            <a class="navbar-brand" href="#">
                <img src="../img/logo.png" alt="">
            </a>

            <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    
                    <li class="nav-item">
                        <a class="nav-link" href="#">Features</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">About</a>
                    </li>
                    
                    <li class="nav-item">
                        <a class="nav-link" href="#">Blog</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link" href="#">Store</a>
                    </li>

                    <!-- <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Dropdown link
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li> -->

                    <button type="button" class="btn btn-primary mx-3 px-3 rounded-pill">Schedule a workout</button>


                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default{
    data(){
        return{
            // links:[
            //     {home:'Home'},
            //     {blog:'Blog'},
            //     {service:
            //         {
            //             nameMenu:'Service',
            //             serviceMenu:[
            //                 'All Service',
            //                 'Service Single Page'
            //             ],
            //         }, 
            //     },
            //     {about:
            //         {
            //         nameMenu:'About',
            //             aboutMenu:[
            //                 'About Me',
            //                 'Our Sponsor',
            //                 'contact'
            //             ]
            //         }
            //     },

            //     {video:{
            //             nameMenu:'Video',
            //             videoMenu:[
            //                 'All Playlist',
            //                 'Playlist Page',
            //                 'Video Single Page'
            //             ],  
            //         },
            //     },  
            //     {store:
            //         {
            //             nameMenu:'Store',
            //             storeMenu:[
            //                 'Simple product',
            //                 'variable product'
            //             ], 
            //         }
            //     }
            // ]
        }
    }
}
</script>

<style lang="scss" scoped>
.navbar {
    background-color: black;
    height: 100px;
    padding: 0 18px;

    .nav-item>a {
        color: white;
    }
}
</style>