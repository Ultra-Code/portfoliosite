<template>
  <section class="has-background-white-ter section">
    <div class="tile is-ancestor">
      <div class="tile is-parent is-one-quarter-tablet">
        <article class="tile is-child notification">
          <figure class="image is-1by1">
            <img
              src="../../assets/images/animal/lonely_dog.jpg"
              class="square-img"
              loading="lazy"
              alt
            />
          </figure>
          <p class="title">Vertical...</p>
          <p class="subtitle">Top tile</p>
        </article>
      </div>
      <div class="tile is-parent is-one-quarter-tablet">
        <article class="tile is-child notification">
          <figure class="image is-1by1">
            <img
              src="../../assets/images/nature/sunny_nature.jpg"
              class="square-img"
              loading="lazy"
              alt
            />
          </figure>
          <p class="title">...tiles</p>
          <p class="subtitle">Bottom tile</p>
        </article>
      </div>
      <div class="tile is-parent is-one-quarter-tablet">
        <article class="tile is-child notification">
          <figure class="image is-1by1">
            <img
              class="square-img"
              src="../../assets/images/work/laptop_desk.jpg"
              loading="lazy"
              alt
            />
          </figure>
          <p class="title">Middle tile</p>
          <p class="subtitle">With an image</p>
        </article>
      </div>
      <div class="tile is-parent is-one-quarter-tablet">
        <article class="tile is-child notification">
          <figure class="image is-1by1">
            <img
              src="../../assets/images/work/work_hallway.jpg"
              class="square-img"
              loading="lazy"
              alt
            />
          </figure>
          <p class="title">Wide tile</p>
          <p class="subtitle">Aligned with the right tile</p>
        </article>
      </div>
      <div class="tile is-parent is-one-quarter-tablet">
        <article class="tile is-child notification">
          <figure class="image is-1by1">
            <img src="../../assets/images/nature/nature.jpg" alt class="square-img" />
          </figure>
          <div class="content">
            <p class="title">Tall tile</p>
            <p class="subtitle">With even more content</p>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.bg-light {
  background-color: #f8f9fa !important;
}
.square-img {
  border-radius: 7%;
}
</style>
