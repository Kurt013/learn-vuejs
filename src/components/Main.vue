<script setup>
    import { ref } from 'vue';

    const facts = ref([
        {
            adjective: 'Lightweight',
            description: 'I am incredibly small and fast! My core library is only around 30KB, so I won\'t drag you down.'
        },
        {
            adjective: 'Approachable',
            description: 'Easy to learn and use, even for beginners. I have a gentle learning curve, clear documentation, and a supportive community.'
        },
        {
            adjective: 'Versatile',
            description: 'I can handle everything from simple interactive elements to complex single-page applications. I\'m great for small projects and large-scale applications alike.'
        }
    ]);
</script>

<template>

  <main>
    <section v-for="fact in facts" :key="fact.adjective">
      <h2>I'm <span class="highlight"> {{ fact.adjective }} </span></h2>
      <p>{{ fact.description  }}</p>
    </section>
  </main>
</template>

<style scoped>

</style>
