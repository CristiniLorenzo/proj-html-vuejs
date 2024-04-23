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
                <ul class="d-flex">
                    <li>home <i class="fa-solid fa-chevron-down"></i></li>
                    <li>home <i class="fa-solid fa-chevron-down"></i></li>
                    <li>home</li>
                    <li>home <i class="fa-solid fa-chevron-down"></i></li>
                    <li>home <i class="fa-solid fa-chevron-down"></i></li>
                    <li>home <i class="fa-solid fa-chevron-down"></i></li>
                    <li>home </li>
                </ul>
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