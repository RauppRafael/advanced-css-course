<template>
  <main>
    <app-about></app-about>
    <app-features></app-features>
    <app-tours></app-tours>
    <app-stories></app-stories>
  </main>
</template>

<script>
  import AppAbout from './sections/About.vue';
  import AppFeatures from './sections/Features.vue';
  import AppTours from './sections/tours/Tours.vue';
  import AppStories from './sections/stories/Stories.vue';

  export default {
    name: 'home',
    components: {
      AppAbout,
      AppFeatures,
      AppTours,
      AppStories
    }
  }
</script>

<style>
</style>

