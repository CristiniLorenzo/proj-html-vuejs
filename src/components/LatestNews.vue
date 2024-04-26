<script>
export default {
    name: 'LatestNews',
}
</script>

<template>
    <section>
        <div class="small-container">
            <div class="title">
                <div class="sub-title">
                    The news what we have
                </div>
                <h2>
                    GOGREEN LATEST <span>NEWS</span> FEED
                </h2>
            </div>
            <div class="news d-flex">
                <div class="col-4">
                    <div class="card">
                        <img src="/src/assets/assets/blo1-390x250.jpg" alt="">
                        <div>
                            <i class="fa-solid fa-user"></i> Gogreen <i class="fa-regular fa-clock"></i> 17 Dec 2022
                        </div>
                        <h3>
                            Where i live, i am sourrounded by fresh, organic food, so i eat really well.
                        </h3>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae, velit. Commodi, qui ab dolorem dicta modi, praesentium ea error corporis iste, porro sunt reprehenderit quis architecto illo itaque eos aspernatur?
                        </p>
                        <div class="read">READ MORE...</div>
                    </div>
                    
                </div>
                <div class="col-4">
                    <div class="card">
                        <img src="/src/assets/assets/blo2-390x250.jpg" alt="">
                        <div>
                            <i class="fa-solid fa-user"></i> Gogreen <i class="fa-regular fa-clock"></i> 17 Dec 2022
                        </div>
                        <h3>
                            Where i live, i am sourrounded by fresh, organic food, so i eat really well.
                        </h3>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae, velit. Commodi, qui ab dolorem dicta modi, praesentium ea error corporis iste, porro sunt reprehenderit quis architecto illo itaque eos aspernatur?
                        </p>
                        <div class="read">READ MORE...</div>
                    </div>
                    
                </div>
                <div class="col-4">
                    <div class="card">
                        <img src="/src/assets/assets/blo3-390x250.jpg" alt="">
                        <div>
                            <i class="fa-solid fa-user"></i> Gogreen <i class="fa-regular fa-clock"></i> 17 Dec 2022
                        </div>
                        <h3>
                            Where i live, i am sourrounded by fresh, organic food, so i eat really well.
                        </h3>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae, velit. Commodi, qui ab dolorem dicta modi, praesentium ea error corporis iste, porro sunt reprehenderit quis architecto illo itaque eos aspernatur?
                        </p>
                        <div class="read">READ MORE...</div>
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
    padding: 75px 0;
    .title{
        background-image: url(/src/assets/assets/title-shap.png);
        background-repeat: no-repeat;
        background-position: center;
        background-size: contain;
        padding-top: 30px;
        text-align: center;

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
    .news{
        padding: 30px 0;
        .card{
            width: 95%;
            i{
                color: $brand-yellow;
            }
            h3{
                color: $brand-green;
                font-weight: 700;
                font-size: 20px;
            }
            p{
                color: $brand-lightgray;
            }
            .read{
                color: $brand-green;
                font-weight: 700;
            }
        }
    }
}

</style>