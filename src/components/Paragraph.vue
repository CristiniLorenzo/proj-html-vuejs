<script>

export default {
    name: 'Paragraph',
    
}
</script>

<template>
    <section>
        <div><i class="fa-solid fa-quote-left"></i></div>
        <p>
            "Dessert pudding dessert jelly beans cupcake sweet caramels gingerbread. Fruitcake biscuit cheesecake.
            Cookie topping sweets muffine pudding tart bear claw sugar plum croissant." We started as a small legal consultancy. 
            We have proved our competence and had many stisfied clients.
        </p>
        <div>
            <h4>Martha Alex</h4>
        </div>
        <div class="text-orange">
            Manager
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

section{
    text-align: center;
    padding: 75px;
    width: 50%;
    margin: 0 auto;
    i{
        font-size: 75px;
        color: $brand-green;
    }
    p{
        line-height: 25px;
        font-weight: 600;
        font-size: 17px;
    }
    h4{
        font-weight: 700;
    }
    .text-orange{
        color: $brand-yellow;
        font-weight: 700;
    }
}
</style>