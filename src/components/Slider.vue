<script >
export default {
    name: 'Slider',
}
</script>

<template>
    <div id="carouselExampleCaptions" class="carousel slide">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="/src/assets/assets/H3-slider3.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block car-text">
                    <div>
                        <h5>GOGREEN ORGANIC FOOD STORE</h5>
                        <h1>Eating naturally & organic is always be healthy</h1>
                        <div class="buttons d-flex justify-content-center">
                            <button class="about-us ">ABOUT US</button>
                        
                            <button class="history">OUR HISTORY</button>
                        </div>
                    </div>
                    
                    
                </div>
            </div>
            <div class="carousel-item">
                <img src="/src/assets/assets/slider.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Second slide label</h5>
                    <p>Some representative placeholder content for the second slide.</p>
                </div>
            </div>
    
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>

    
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

.car-text{
    margin-bottom: 250px;
    h1{
        font-weight: 700;
        font-size: 90px;
    }
    .buttons{
    button{
    margin: 30px 10px;
    }
        .about-us{
        background-color: $brand-yellow;
        border: none;
        color: $brand-white;
        padding: 15px 40px;
        font-size: 14px;
        //TO CHANGE HOVER
        border-top-right-radius: 20px;
        border-end-start-radius: 20px;
        //
        }
        .history{
        background-color: $brand-green;
        border: none;
        color: $brand-white;
        padding: 15px 40px;
        font-size: 14px;
        //TO CHANGE HOVER
        border-top-right-radius: 20px;
        border-end-start-radius: 20px;
        }
    }
}


</style>


