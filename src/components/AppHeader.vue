<script >
import HeaderTop from './HeaderTop.vue';
import HeaderBottom from './HeaderBottom.vue'



export default {
    name: 'AppHeader',

    components: {
        HeaderTop,
        HeaderBottom,
    },
}
</script>

<template>
<HeaderTop></HeaderTop>
<HeaderBottom></HeaderBottom>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;
</style>
