<template>
  <section class="section-features">

    <div class="row">

      <div class="col-1-of-4">
        <div class="feature-box">
          <i class="feature-box__icon icon-basic-world"></i>
          <h3 class="heading-tertiary u-mb-sm">
            Explore the world
          </h3>
          <p class="feature-box__text">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda at autem blanditiis
            doloribus enim eos expedita fugit nihil.
          </p>
        </div>
      </div>

      <div class="col-1-of-4">
        <div class="feature-box">
          <i class="feature-box__icon icon-basic-compass"></i>
          <h3 class="heading-tertiary u-mb-sm">
            Meet nature
          </h3>
          <p class="feature-box__text">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda at autem blanditiis
            doloribus enim eos expedita fugit nihil.
          </p>
        </div>
      </div>

      <div class="col-1-of-4">
        <div class="feature-box">
          <i class="feature-box__icon icon-basic-map"></i>
          <h3 class="heading-tertiary u-mb-sm">
            Find your way
          </h3>
          <p class="feature-box__text">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda at autem blanditiis
            doloribus enim eos expedita fugit nihil.
          </p>
        </div>
      </div>

      <div class="col-1-of-4">
        <div class="feature-box">
          <i class="feature-box__icon icon-basic-heart"></i>
          <h3 class="heading-tertiary u-mb-sm">
            Live a healthier life
          </h3>
          <p class="feature-box__text">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda at autem blanditiis
            doloribus enim eos expedita fugit nihil.
          </p>
        </div>
      </div>

    </div>

  </section>
</template>

<script>
</script>

<style lang="scss" scoped>
  @import "~sassResources";

  .section-features {
    padding: 20rem 0;
    transform: skewY(-7deg);
    margin-top: -10rem;
    @include background-img-gradient('/src/assets/img/nat-4.jpg');

    & > * {
      transform: skewY(7deg);
    }
  }
</style>

