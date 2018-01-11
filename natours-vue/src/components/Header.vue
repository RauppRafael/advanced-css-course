<template>
  <header class="header">
    <div class="header__logo-box">
      <img src="/src/assets/img/logo-white.png" alt="logo" class="header__logo">
    </div>

    <div class="header__text-box">
      <h1 class="heading-primary">
        <span class="heading-primary--main">Outdoors</span>
        <span class="heading-primary--sub">is where life happens</span>
      </h1>
      <a href="#" class="btn btn--white btn--animated">Discover our tours</a>
    </div>
  </header>
</template>

<style lang="scss" scoped>
  @import '../assets/sass/abstracts/variables';
  @import '../assets/sass/abstracts/mixins';

  .header {
    @include background-img-gradient('/src/assets/img/hero.jpg');
    @include clip-path(75vh);
    height: 95vh;
    position: relative;
    animation: hiddenToVisible .75s;

    &__logo-box {
      position: absolute;
      top: 4rem;
      left: 4rem;
    }

    &__logo {
      height: 3.5rem;
      animation: hiddenToVisible 1.5s;
    }

    &__text-box {
      position: absolute;
      top: 42%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
    }
  }
</style>

