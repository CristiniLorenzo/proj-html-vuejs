<script>
export default {
    name: 'EmergencyLink',

    props: ['info']
}
</script>

<template>
    <div>
        <li>{{ info.text }}</li>
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
@use '../style/generics.scss' as *;

li{
    list-style: none;
    padding: 10px 0;
}
</style>