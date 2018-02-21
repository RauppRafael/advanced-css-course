<template>
  <section class="section-about">
    <div class="u-center-text">
      <h2 class="heading-secondary u-mb-lg">
        Exciting tours for adventurous people
      </h2>
    </div>

    <div class="row">
      <div class="col-1-of-2">
        <h3 class="heading-tertiary u-mb-sm">You're going to fall in love with nature</h3>
        <p class="paragraph">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias at expedita explicabo hic id
          labore mollitia optio qui tempore, veniam. Aliquam aspernatur assumenda, natus numquam
          possimus reiciendis similique tempora. Tempore!
        </p>

        <h3 class="heading-tertiary u-mb-sm">
          Live adventures like you have never before
        </h3>
        <p class="paragraph">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias at expedita explicabo hic id
          labore mollitia optio qui tempore, veniam. Aliquam aspernatur assumenda, natus numquam
          possimus reiciendis similique tempora. Tempore!
        </p>

        <a href="#" class="btn-text">Learn more &rarr;</a>
      </div>
      <div class="col-1-of-2">
        <div class="composition">
          <img src="/src/assets/img/nat-1.jpg" alt="Photo 1" class="composition__photo composition__photo--1">
          <img src="/src/assets/img/nat-2.jpg" alt="Photo 2" class="composition__photo composition__photo--2">
          <img src="/src/assets/img/nat-3.jpg" alt="Photo 3" class="composition__photo composition__photo--3">
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
  @import '../../../assets/sass/abstracts/variables';

  .section-about {
    background-color: $color-grey--light--1;
    padding: 25rem 0;
    margin-top: -20vh;
  }
</style>

