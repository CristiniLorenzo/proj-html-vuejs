<script >
import Slider from './Slider.vue';
import Consumer from './Consumer.vue';
import ShopArea from './ShopArea.vue';
import Paragraph from './Paragraph.vue';
import Infos from './Infos.vue';
import Trending from './Trending.vue';




export default {
    name: 'AppMain',
    components: {
        Slider,
        Consumer,
        ShopArea,
        Paragraph,
        Infos,
        Trending
    },
}
</script>

<template>
  <Slider></Slider>
  <Consumer></Consumer>
  <ShopArea></ShopArea>
  <Paragraph></Paragraph>
  <Infos></Infos>
  <Trending></Trending>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
</style>
