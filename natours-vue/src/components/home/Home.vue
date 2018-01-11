<template>
  <main>
    <app-about></app-about>
    <app-features></app-features>
    <app-tours></app-tours>
  </main>
</template>

<script>
  import AppAbout from './sections/About.vue';
  import AppFeatures from './sections/Features.vue';
  import AppTours from './sections/Tours.vue';

  export default {
    name: 'home',
    components: {
      AppAbout,
      AppFeatures,
      AppTours
    }
  }
</script>

<style>
</style>

