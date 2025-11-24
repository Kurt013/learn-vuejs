<script setup>
    import { ref } from 'vue';
    const href = ref("https://vuejs.org/");
</script>

<template>
    <footer>
        <p>Learn more about Vue at <a :href>vuejs.org</a></p>
    </footer>
</template>

