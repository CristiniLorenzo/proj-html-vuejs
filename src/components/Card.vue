<script>
export default {
    name: 'Card',
}
</script>

<template>
    <div class="col-3">
        <div class="image">
            <img src="/src/assets/assets/s5.jpg" alt="">
        </div>
        <h4>Fresh Apple</h4>
        <p class="price">$18</p>
    </div>
    <div class="col-3">
        <div class="image position-relative">
            <img src="/src/assets/assets/s2.jpg" alt="">
            <span class="sale position-absolute">SALE!</span>
        </div>
        <h4>Fresh Apple</h4>
        <p class="price"><span class="discount">$29</span> $18</p>
    </div>
    <div class="col-3">
        <div class="image">
            <img src="/src/assets/assets/s8.jpg" alt="">
        </div>
        <h4>Fresh Apple</h4>
        <p class="price">$18</p>
    </div>
    <div class="col-3">
        <div class="image position-relative">
            <img src="/src/assets/assets/s1.jpg" alt="">
            <span class="sale position-absolute">SALE!</span>
        </div>
        <h4>Fresh Apple</h4>
        <p class="price"><span class="discount">$29</span> $18</p>
    </div>
    <div class="col-3">
        <div class="image position-relative">
            <img src="/src/assets/assets/s4.jpg" alt="">
            <span class="sale position-absolute">SALE!</span>

        </div>
        <h4>Fresh Apple</h4>
        <p class="price"><span class="discount">$29</span> $18</p>
    </div>
    <div class="col-3">
        <div class="image">
            <img src="/src/assets/assets/s10.jpg" alt="">
        </div>
        <h4>Fresh Apple</h4>
        <p class="price">$18</p>
    </div>
    <div class="col-3">
        <div class="image position-relative">
            <img src="/src/assets/assets/s9.jpg" alt="">
            <span class="sale position-absolute">SALE!</span>

        </div>
        <h4>Fresh Apple</h4>
        <p class="price"><span class="discount">$29</span> $18</p>
    </div>
    <div class="col-3">
        <div class="image">
            <img src="/src/assets/assets/s7.jpg" alt="">
        </div>
        <h4>Fresh Apple</h4>
        <p class="price">$18</p>
    </div>
    
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

img{
    width: 90%;
}
.sale{
    top: 8px;
    right: 20px;
    background-color: $brand-yellow;
    padding: 8px;
}
.price{
    color: $brand-yellow;
    .discount{
        text-decoration: line-through;
        opacity: 0.6;
    }
}

</style>