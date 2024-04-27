<script>
export default {
    name: 'Newsletter',
}
</script>

<template>
    <section>
        <div class="small-container d-flex">
            <div class="col-6">
                <h2>SUBSCRIBE OUR NEWSLETTER</h2>
            </div>
            <div class="col-6">
                <div class="form ">
                    <input type="email" placeholder="your email">
                    <button>send</button>
                </div>
                
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

.small-container{
    background-image: url(/src/assets/assets/counter-bg.jpg);
    padding: 30px;
        h2{
            color: $brand-white;
            margin: 0;
        }
        input{
            padding-left: 20px;
            padding-top: 10px;
            padding-bottom: 10px;
            padding-right: 200px;
        }
        button{
            padding: 12px 50px;
            border: none;
            background-color: $brand-green
        }
        
}

</style>