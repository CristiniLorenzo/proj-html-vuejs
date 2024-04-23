<script >
export default {
    name: 'HeaderTop'
}
</script>

<template>
    <section>
        <div class="container d-flex justify-content-between">
            <div class="left d-flex">
               <div>
                    <i class="fa-solid fa-location-dot"></i>
                    <span>North baukhula, tala, USA</span>
               </div> 
               <div>
                    <i class="fa-solid fa-envelope"></i>
                    <span>demo@example.com</span>
               </div> 
            </div>
            <div class="right d-flex">
                <div class="hour">
                    <i class="fa-regular fa-clock"></i>
                    <span>8.30AM-8.30PM</span>
               </div> 
               <div class="socials">
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-instagram"></i>
                    <i class="fa-brands fa-pinterest-p"></i>
               </div> 
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

section{
    background-color: $brand-green;
    padding: 18px 0;
    color: $brand-white;
    font-size: 14px;
        .container{
            padding: 0;
                .left{
                div{
                    padding-right: 15px;
                }
                i{
                    padding-right: 5px;
                }
            } 
            .right{
                div{
                    padding-left: 15px;
                }
                i{
                    padding-right: 10px;
                }
                .hour{
                    padding-right: 15px;
                }
                .socials{
                    .fa-pinterest-p{
                        padding: 0;
                    }
                }
            }
        }
        

}

</style>