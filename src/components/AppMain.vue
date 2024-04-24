<script >
import Slider from './Slider.vue';
import Consumer from './Consumer.vue';
import ShopArea from './ShopArea.vue';


export default {
    name: 'AppMain',
    components: {
        Slider,
        Consumer,
        ShopArea
    },
}
</script>

<template>
  <Slider></Slider>
  <Consumer></Consumer>
  <ShopArea></ShopArea>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
</style>
