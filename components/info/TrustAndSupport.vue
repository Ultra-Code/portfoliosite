<template>
  <div class="py-5">
    <div class="container">
      <div class="title has-text-centered">
        <h2>Trusted By ~</h2>
      </div>
      <div class="columns is-vcentered is-mobile">
        <div class="column is-2-mobile is-4-desktop my-3 img-size">
          <a href="#!">
            <img class="image is-centered" src="../../assets/images/logos/logos.jpg" alt />
          </a>
        </div>
        <div class="column is-2-mobile is-4-desktop my-3 img-size">
          <a href="#!">
            <img
              class="image is-centered"
              src="../../assets/images/logos/KFC_logo_emblem_logotype.png"
              alt
            />
          </a>
        </div>
        <div class="column is-2-mobile is-4-desktop my-3 img-size">
          <a href="#!">
            <img class="image is-centered" src="../../assets/images/logos/EA_logo_com.png" alt />
          </a>
        </div>
        <div class="column is-2-mobile is-4-desktop my-3 img-size">
          <a href="#!">
            <img class="image is-centered" src="../../assets/images/logos/Addidas Symbol.jpg" alt />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.img-size {
  max-width: 100%;
  height: auto;
  width: 5rem;
  display: block;
}
@media (min-width: 768px) {
  .img-size {
    margin-left: 1.5rem;
    margin-right: 1.5rem;
    width: 9rem;
  }
}
@media (min-width: 968px) {
  .img-size {
    margin-left: 3rem;
    margin-right: 3rem;
    width: 12rem;
  }
}
</style>
