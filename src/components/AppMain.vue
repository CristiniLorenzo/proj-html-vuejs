<script >
import Slider from './Slider.vue';
import Consumer from './Consumer.vue';
import ShopArea from './ShopArea.vue';
import Paragraph from './Paragraph.vue';



export default {
    name: 'AppMain',
    components: {
        Slider,
        Consumer,
        ShopArea,
        Paragraph
    },
}
</script>

<template>
  <Slider></Slider>
  <Consumer></Consumer>
  <ShopArea></ShopArea>
  <Paragraph></Paragraph>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
</style>
