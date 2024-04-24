<script >
export default {
    name: 'HeaderBottom'
}
</script>

<template>
    <section>
        <div class="container d-flex align-items-center position-relative">
            <div class="left">
                <img src="../assets/assets/logo.png" alt="">
            </div>

            <div class="mid d-flex align-items-center">
                <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
                    <div class="container-fluid">
                        <a class="navbar-brand" href="#">Navbar</a>
                        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDarkDropdown" aria-controls="navbarNavDarkDropdown" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse" id="navbarNavDarkDropdown">
                        <ul class="navbar-nav">
                            <li class="nav-item dropdown">
                                <button class="btn dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
                                    Home
                                </button>
                                <ul class="dropdown-menu dropdown-menu-dark">
                                    <li><a class="dropdown-item" href="#">Action</a></li>
                                    <li><a class="dropdown-item" href="#">Another action</a></li>
                                    <li><a class="dropdown-item" href="#">Something else here</a></li>
                                </ul>
                            </li>
                            <li class="nav-item dropdown">
                                <button class="btn dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
                                    Dropdown
                                </button>
                                <ul class="dropdown-menu dropdown-menu-dark">
                                    <li><a class="dropdown-item" href="#">Action</a></li>
                                    <li><a class="dropdown-item" href="#">Another action</a></li>
                                    <li><a class="dropdown-item" href="#">Something else here</a></li>
                                </ul>
                            </li>
                        </ul>
                        </div>
                    </div>
                </nav>
            </div>

            <div class="right d-flex align-items-center position-absolute end-0">
                <button class="search">
                    <i class="fa-solid fa-magnifying-glass"></i> 
                </button>
                <button class="shop position-relative">
                    <i class="fa-solid fa-cart-shopping"></i>
                    <span class="n-article position-absolute top-1 start-100 translate-middle ">0</span>
                </button>
                <button class="order">ORDER NOW</button>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

section{
    padding: 15px 0;
    .container{
        padding: 0;
    .left{
        padding-right: 30px;
        img{
            height: 45px;
        }
    }
    .mid{
        ul{
            list-style: none;
                li{
                  padding: 0 10px;  
                    i{
                        font-size: 12px;
                        color: $brand-lightgray;
                    }
                }
        }
    }
    .right{
        button{
            margin-left: 20px;
        }
        .search{
            background-color: $brand-yellow;
            color: $brand-white;
            height: 35px;
            width: 35px;
            border-radius: 50%;
            border: none;
            padding: 8px;
            font-size: 14px;
        }
        .shop{
            background-color: $brand-white;
            border: none;
            i{
                color: $brand-green;
            }
            .n-article{
                font-size: 12px;
                background-color: $brand-yellow;
                border-radius: 50%;
                height: 14px;
                width: 14px;
                color: $brand-white;
            }
        }
        .order{
            background-color: $brand-yellow;
            border: none;
            color: $brand-white;
            padding: 15px;
            font-size: 14px;
            //TO CHANGE HOVER
            border-top-right-radius: 20px;
            border-end-start-radius: 20px;
            //
        }
    }
}
}


</style>