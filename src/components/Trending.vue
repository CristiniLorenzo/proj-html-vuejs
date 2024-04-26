<script>
export default {
    name: 'Trending',
}
</script>

<template>
    <section>
        <div class="small-container">
            <div class="title">
                <div class="sub-title">
                    Running week top selling
                </div>
                <h2>
                    TOP <span>TRENDING</span> ORGANIC FOOD
                </h2>
            </div>
            <div class="trend-products d-flex">
                <div class="col-3">
                    <div class="card">
                        <img src="/src/assets/assets/s5.jpg" alt="">
                        <h3>Fresh Apple</h3>
                        <div>$18</div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <img src="/src/assets/assets/s2.jpg" alt="">
                        <h3>Fresh Apple</h3>
                        <div>$18</div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <img src="/src/assets/assets/s8.jpg" alt="">
                        <h3>Fresh Apple</h3>
                        <div>$18</div>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card">
                        <img src="/src/assets/assets/s1.jpg" alt="">
                        <h3>Fresh Apple</h3>
                        <div>$18</div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

.small-container{
    padding: 50px 0;
    text-align: center;
    .title{
        background-image: url(/src/assets/assets/title-shap.png);
        background-repeat: no-repeat;
        background-position: center;
        background-size: contain;
        padding-top: 30px;
        .sub-title{
            color: $brand-yellow;
            font-weight: 700;
        }
        h2{
            color: $brand-green;
            font-weight: 700;
            span{
                color: $brand-yellow;
            }
        }
    }
    .card{
        box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
        padding-bottom: 20px;
        width: 90%;
        margin: 30px 0;
    }
    
}

</style>