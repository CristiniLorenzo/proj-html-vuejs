<script>
export default {
    name: 'Logos',
}
</script>

<template>
    <section>
        <div class="small-container d-flex">
            <div class="col">
                <img src="/src/assets/assets/brand1-100x100.png" alt="">
            </div>
            <div class="col">
                <img src="/src/assets/assets/brand4.png" alt="">
            </div>
            <div class="col">
                <img src="/src/assets/assets/brand3.png" alt="">
            </div>
            <div class="col">
                <img src="/src/assets/assets/brand1-100x100.png" alt="">
            </div>
            <div class="col">
                <img src="/src/assets/assets/brand2.png" alt="">
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

.small-container{
    padding: 50px 0;
    .col{
        width: calc(100% / 5);
        text-align: center;
        img{
            height: 100%;
        }
    }
}

</style>