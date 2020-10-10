<template>
  <section class="container section">
    <div class="container">
      <div class="services has-text-centered is-size-3 mb-3">At Your Service</div>
      <div
        class="has-text-centered"
      >Lorem ipsum dolor sit amet consectetur, adipisicing elit. Repudiandae veniam dicta neque</div>
    </div>
    <hr class="has-text-warning" />
    <div class="container">
      <div class="level">
        <div class="level-item has-text-centered">
          <div>
            <b-icon pack="fas" icon="home" size="is-large" type="is-info"></b-icon>
            <h1 class="heading is-size-6 mb-2">We Make You Feel At Home</h1>
            <p class="heading">
              Lorem ipsum dolor sit amet
              <br />consectetur adipisicing elit.
              <br />ipsa quisquam repellendus modi quam labore.
            </p>
          </div>
        </div>
        <div class="level-item has-text-centered">
          <div>
            <b-icon pack="fas" icon="luggage-cart" size="is-large" type="is-info"></b-icon>
            <h1 class="heading is-size-6 mb-2">We Take Care Of Your Travels</h1>
            <p class="heading">
              Lorem ipsum dolor sit amet
              <br />consectetur adipisicing elit.
              <br />ipsa quisquam repellendus modi quam labore.
            </p>
          </div>
        </div>
        <div class="level-item has-text-centered">
          <div>
            <b-icon pack="fas" icon="chart-pie" size="is-large" type="is-info"></b-icon>
            <h1 class="heading is-size-6 mb-2">We Analyse Your Workflow</h1>
            <p class="heading">
              Lorem ipsum dolor sit amet
              <br />consectetur adipisicing elit.
              <br />ipsa quisquam repellendus modi quam labore.
            </p>
          </div>
        </div>
      </div>
    </div>
    <hr class="has-text-warning" />
    <div class="tags has-addons">
      <span class="tag is-danger">Development Mode</span>
      <span class="tag is-success">Juli Boi What Do You Think</span>
      <span class="tag is-warning">#More Ideas</span>
    </div>
    <div class="columns">
      <card title="Free" pack="fab" icon="github">
        Open source on
        <a href="https://github.com/buefy/buefy">GitHub</a>
      </card>

      <card title="Responsive" icon="mobile-alt">
        <b class="has-text-grey">Every</b> component is responsive
      </card>

      <card title="Modern" pack="fab" icon="accusoft">
        Built with
        <a href="https://vuejs.org/">Vue.js</a> and
        <a href="http://bulma.io/">Bulma</a>
      </card>
    </div>
  </section>
</template>


<style lang="scss" scoped>
div {
  &.services {
    font-family: Piazzolla, Cambria, Cochin, Georgia, Times, 'Times New Roman',
      serif;
    font-weight: 600;
  }
}
</style>
