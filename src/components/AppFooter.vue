<script >
import Newsletter from './Newsletter.vue';


export default {
    name: 'AppFooter',
    components: {
        Newsletter,
        
    },
}
</script>

<template>
  <Newsletter></Newsletter>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
</style>
