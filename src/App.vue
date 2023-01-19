<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
    data() {
        return {
            name: 'Armando',
        }
    },
    components: {
        AppTitle,
        AppHero
    }
}
</script>

<template>
    <AppTitle />
    <AppHero />
</template>

<style>

</style>
