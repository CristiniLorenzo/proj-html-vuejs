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
                <div>
                    <i class="fa-regular fa-clock"></i>
                    <span>8.30AM-8.30PM</span>
               </div> 
               <div>
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
    padding: 18px;
    color: $brand-white;
    font-size: 14px;
        .left{
            div{
                padding: 0 15px;
            }
            i{
                padding-right: 5px;
            }
        } 
        .right{
            div{
                padding: 0 15px;
                i{
                    padding: 0 10px;
                }
            }
        }

}

</style>