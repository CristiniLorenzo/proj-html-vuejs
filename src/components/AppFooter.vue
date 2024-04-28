<script >
import Newsletter from './Newsletter.vue';
import FooterMain from './FooterMain.vue';
import FooterBottom from './FooterBottom.vue';



export default {
  name: 'AppFooter',
  components: {
    Newsletter,
    FooterMain,
    FooterBottom
      
  },
  
}
</script>

<template>
  <Newsletter></Newsletter>
  <FooterMain></FooterMain>
  <FooterBottom></FooterBottom>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
</style>
