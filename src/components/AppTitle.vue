<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'La mia prima app con Vite!',
        }
    }
}
</script>

<template>
    <div class="text-center">
        <h1>{{ title }}</h1>
    </div>
</template>

<style scoped>
h1 {
    color: blue;
}
</style>