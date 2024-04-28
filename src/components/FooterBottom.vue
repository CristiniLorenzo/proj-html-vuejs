<script>
export default {
    name: 'FooterBottom',

}
</script>

<template>
    <section>
        <div class="small-container d-flex justify-content-between align-items-center">
            <div>
                Copyright © gogrin all rights reserved.
            </div>
            <div>
                <ul class="d-flex align-items-center">
                    <li>
                        <a href="#">Service</a>
                    </li>
                    <li>
                        <a href="#">Service</a>
                    </li>
                    <li>
                        <a href="#">Service</a>
                    </li>
                </ul>
            </div>
        </div>
    </section>
    
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

section{
background-color: $brand-green;
color: $brand-white;
padding: 20px 0;

    ul{
    list-style: none;
        li{
        padding: 0 15px;
            a{
                text-decoration: none;
            }
        }      
    }
}
</style>