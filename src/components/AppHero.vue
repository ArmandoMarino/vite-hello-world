<script>
export default {
    name: 'AppHero',
    data() {
        return {
            image: 'banner.jpg',
        }
    },
    methods: {
        buildImagePath(image) {
            const url = new URL(`../assets/img/${image}`, import.meta.url);
            return url.href;
        }
    }
}
</script>

<template>
    <img :src="buildImagePath(image)" alt="">
</template>

<style>

</style>