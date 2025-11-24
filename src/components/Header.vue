<script setup>
    import { ref } from 'vue'

</script>

<template>
    <header>
        <img src="@/assets/vue.svg" alt="Svg Icon">
        <h1>Hi, I'm <span class="highlight">Vue</span></h1>
    </header>
</template>

<style scoped>
    img {
        background-color: white;
        width: 60px;
        padding: 1rem;
    }

    h1 {
        font-size: 2.5rem;
    }
</style>