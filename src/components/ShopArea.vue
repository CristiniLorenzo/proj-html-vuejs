<script>
import Card from './Card.vue';

export default {
    name: 'ShopArea',
    components: {
        Card
    }
}
</script>

<template>
    <section>

        <div class="container position-relative">
            <div class="small-container">
                
                <div class="title">
                    <div class="text-orange">
                        Trending Online Store
                    </div>
                    <h2>
                        <span>GOGREEN ALL </span>
                        <span class="text-orange">ORGANIC </span>
                        <span>FOOD</span> 
                    </h2>
                </div>

                <div class="product-nav ">
                    <ul class="d-flex justify-content-center">
                        <li>All product</li>
                        <li>All product</li>
                        <li>All product</li>
                        <li>All product</li>
                        <li>All product</li>

                    </ul>
                </div>

                <div class="cards-area d-flex flex-wrap">
                    <Card></Card>
                </div>

                <div>
                    <button>ALL PRODUCTS</button>
                </div>
            </div>
            
           
        </div>
        
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

.container{
    background-image: url(/src/assets/assets/shop-bg-img.jpg);
    text-align: center;
    color: $brand-white;

    .small-container{
        padding: 75px;

        ul{
            list-style: none;
            li{
                padding: 25px;
            }
        }
        button{
            border: none;
            background-color: $brand-yellow;
            padding: 15px 35px;
            color: $brand-white;
            border-top-right-radius: 20px;
            border-bottom-left-radius: 20px;

        }
    }
    .text-orange{
            color: $brand-yellow;
        }
    h2{
        
        font-weight: 700;
        
    }
}

</style>