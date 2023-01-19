<script>
export default {
    name: 'AppHero',
    data() {
        return {
            images: ['banner.jpg'],
        }
    },
    methods: {
        buildImagePath(image) {
            const url = new URL(`.assets/img/${image}`, import.meta.url);
            return url.href;
        }
    }
}
</script>

<template>

</template>

<style>

</style>