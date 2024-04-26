<script>
export default {
    name: 'BestFood',
}
</script>

<template>
    <section>
        <div class="container">
            <div class="small-container">
                <div>
                   HERE YOU CAN GET 100% FRESH ORGANIC FOOD 
                </div>
                <h2>
                    Best organic food up to 25% off for all product
                </h2>
                <p>
                    The mnost beautiful people we have known are those who have known defeat, known suffering, known loss, and have found their way out of those depths. The mnost beautiful people we have known are those who have known defeat, known suffering
                </p>
                <div class="buttons">
                    <button class="whatsapp">
                        <i class="fa-brands fa-whatsapp"></i>+088123 56 906
                    </button>
                    <button class="apointment">
                        APOINTMENT
                    </button>
                </div>
            </div>
        </div>

    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

.container{
    background-image: url(/src/assets/assets/call-to-bg.jpg);
    background-size: cover;
    color: $brand-white;
    padding: 75px 0;
    text-align: center;

        h2{
            padding: 20px 0;
            font-size: 40px;
            font-weight: 700;
        }
        .buttons{
            padding: 30px 0;
            .whatsapp{
                color: $brand-white;
                background-color: $brand-yellow;
                border: none;
                padding: 20px 40px;
                border-radius: 5px;
                font-weight: 700;
                margin-right: 30px;
            }
            .apointment{
                color: $brand-white;
                background-color: $brand-green;
                border: none;
                padding: 20px 40px;
                border-radius: 5px;
                font-weight: 700;
            }
        }
}

</style>