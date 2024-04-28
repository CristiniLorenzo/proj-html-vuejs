<script >
import Newsletter from './Newsletter.vue';
import FooterMain from './FooterMain.vue';


export default {
  name: 'AppFooter',
  components: {
    Newsletter,
    FooterMain
      
  },
  
}
</script>

<template>
  <Newsletter></Newsletter>
  <FooterMain></FooterMain>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
</style>
