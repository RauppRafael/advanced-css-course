<template>
  <section class="section-stories">

    <div class="u-center-text u-mb-lg">
      <h2 class="heading-secondary">
        We make people genuinely happy
      </h2>
    </div>

    <div class="row">
      <app-story imgSrc="/src/assets/img/nat-8.jpg">
        <span slot="heading">I had the best week ever with my family</span>
        <span slot="text">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. A aliquam assumenda delectus,
        dignissimos ea facere ipsa laudantium natus pariatur perspiciatis quae
        quas quidem quis repellat vel! Accusantium architecto distinctio rerum.
        </span>
      </app-story>
    </div>

    <div class="row">
      <app-story imgSrc="/src/assets/img/nat-8.jpg">
        <span slot="heading">I had the best week ever with my family</span>
        <span slot="text">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. A aliquam assumenda delectus,
        dignissimos ea facere ipsa laudantium natus pariatur perspiciatis quae
        quas quidem quis repellat vel! Accusantium architecto distinctio rerum.
        </span>
      </app-story>
    </div>

  </section>
</template>

<script>
  import AppStory from './Story.vue';

  export default {
    components: {
      AppStory
    }
  }
</script>

<style lang="scss" scoped>
  @import '~sass/abstracts/variables';

  .section-stories {
    padding: 15rem 0;
    background-color: $color-grey--light--1;
  }
</style>

