<template>
  <section class="section-tours">

    <div class="u-center-text">
      <h2 class="heading-secondary u-mb-lg">
        Most popular tours
      </h2>
    </div>

    <div class="row">

      <div class="col-1-of-3">
        <app-card></app-card>
      </div>

      <div class="col-1-of-3">
        <app-card></app-card>
      </div>

      <div class="col-1-of-3">
        <app-card></app-card>
      </div>

    </div>

  </section>
</template>

<script>
  import AppCard from './Card.vue';

  export default {
    components: {
      AppCard
    }
  }
</script>

<style lang="scss" scoped>
  @import '../../../../assets/sass/abstracts/variables';

  .section-tours {
    background-color: $color-grey--light--1;
    padding: 25rem 0;
    margin-top: -10rem;
    padding-bottom: 50rem;
  }
</style>

