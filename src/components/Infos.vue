<script>
export default {
    name: 'Infos',
}
</script>

<template>
    <section>

        <div class="container">
            <div class="small-container d-flex">
                <div class="col-3 d-flex align-items-center justify-content-center">
                    <div>
                        <h2>29+</h2>
                        <div class="text">Year of Experienced</div>
                    </div>
                    <img src="/src/assets/assets/counter-shap1.png" alt="">
                </div>
                <div class="col-3 d-flex align-items-center justify-content-center">
                    <div>
                        <h2>29+</h2>
                        <div class="text">Year of Experienced</div>
                    </div>
                    <img src="/src/assets/assets/counter-shap1.png" alt="">
                </div>
                <div class="col-3 d-flex align-items-center justify-content-center">
                    <div>
                        <h2>29+</h2>
                        <div class="text">Year of Experienced</div>
                    </div>
                    <img src="/src/assets/assets/counter-shap1.png" alt="">
                </div>
                <div class="col-3 d-flex align-items-center justify-content-center">
                    <div>
                        <h2>29+</h2>
                        <div class="text">Year of Experienced</div>
                    </div>
                </div>
            </div>
        </div>

    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

.container{
    background-image: url(/src/assets/assets/counter-bg.jpg);

        .col-3{
            padding: 30px 0;
            text-align: center; 
            h2{
                color: $brand-yellow;
                font-size: 50px;
                font-weight: 700;
            }
            .text{
                color: $brand-white;
                font-weight: 700;
            }
            img{
                height: 75%;
                padding: 0 25px;
            }
        }
}

</style>