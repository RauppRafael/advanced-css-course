<template>
  <div class="story">
    <figure class="story__shape">
      <img :src="imgSrc" alt="Story img" class="story__img">
      <figcaption class="story__caption">
        Mary Smith
      </figcaption>
    </figure>
    <div class="story__text">
      <h3 class="heading-tertiary u-mb-sm">
        <slot name="heading"></slot>
      </h3>
      <p>
        <slot name="text"></slot>
      </p>
    </div>
  </div>
</template>

<script>
  export default {
    props: {
      imgSrc: {
        type: String,
        required: true
      }
    }
  }
</script>

<style lang="scss" scoped>
  @import "~sassResources";

  .story {
    width: 75%;
    margin: 0 auto;
    box-shadow: 0 3rem 6rem rgba($color-black, .1);
    background-color: $color-white;
    border-radius: .3rem;
    padding: 6rem;
    padding-left: 9rem;
    font-size: $default-font-size;
    transform: skewX(-12deg);
    transition: all .2s;

    &__shape {
      $circle: circle(50% at 50% 50%);

      width: 15rem;
      height: 15rem;
      background-color: pink;
      float: left;
      -webkit-shape-outside: $circle;
      shape-outside: $circle;
      -webkit-clip-path: $circle;
      clip-path: $circle;
      transform: translateX(-3rem) skewX(12deg);
      position: relative;
      overflow: hidden;
    }

    &__img {
      height: 100%;
      transform: translateX(-4rem) scale(1.4);
      backface-visibility: hidden;
      transition: all .5s;
    }

    &__text {
      transform: skewX(12deg);
    }

    &__caption {
      // position
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, 50%);
      // font
      color: $color-white;
      text-transform: uppercase;
      font-size: 1.7rem;
      text-align: center;
      //transition
      opacity: 0;
      transition: all .5s;
      backface-visibility: hidden;
    }

    &:hover {
      transform: skewX(-12deg) scale(1.05);
      box-shadow: 0 4.5rem 7rem rgba($color-black, .125);

      & .story__caption {
        transform: translate(-50%, -50%);
        opacity: 1;
      }

      & .story__img {
        transform: translateX(-4rem) scale(1);
        filter: blur(3px) brightness(80%);
      }
    }
  }
</style>

