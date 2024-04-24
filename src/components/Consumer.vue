<script>
export default {
    name: 'Consumer',
}
</script>

<template>
    <section>

        <div class="container position-relative">
            <div class="small-container d-flex flex-wrap">
                <div class="col-6 colored-text">
                    <span class="text-orange">Look what</span>
                    <span class="text-green"> consumer power has done with</span>
                    <span class="text-orange"> organic food;</span>
                    <span class="text-green"> we can do the sam with clothes.</span>
                </div>
                <div class="col-6 paragraph">
                    <p>
                        <span>
                            I have a need to make these sorts of connections literal sometimes, and a vehicle often helps to do that.
                            I have a relationship to hosting culture. <span class="text-orange"> It isn't really about it helps to do that. I have a relationship to hosting culture</span>
                        </span>
                    </p>
                    <p>
                        <span>
                            I have a need to make these sorts of connections literal sometimes, and a vehicle often helps to do that.
                            I have a relationship to hosting culture. 
                        </span>
                    </p>
                </div>
                <div class="col-3">
                    <img src="/src/assets/assets/fe3.jpg" alt="">
                </div>
                <div class="col-3">
                    <img src="/src/assets/assets/fe1.jpg" alt=""> 
                </div>
                <div class="col-3">
                    <img src="/src/assets/assets/fe2.jpg" alt="">
                </div>
                <div class="col-3">
                    <img src="/src/assets/assets/fe1.jpg" alt="">
                </div>
            </div>

            <img class="position-absolute top-0 end-0 all-natural" src="/src/assets/assets/fe-shap1-1.png" alt="">
        </div>
        
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;
.container{
    padding: 75px 0;
    .colored-text{
    font-size: 45px;
    font-weight: 700;
    
        .text-green{
        color: $brand-green;
        }

    }
    .paragraph{
        color: $brand-lightgray;
    }
    .text-orange{
        color: $brand-yellow;
    }
    .all-natural{
        width: 200px;
        margin-top: 50px;
        
    }
}


</style>