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
    <div class="container">
        <img class="img-fluid" :src="buildImagePath(image)" alt="">
    </div>
</template>

<style scoped>
.container img {
    width: 800px;
}
</style>