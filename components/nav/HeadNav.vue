<template>
  <div class="bg hero is-large">
    <div class="hero-head">
      <div class="container">
        <b-navbar centered>
          <template slot="brand">
            <b-navbar-item tag="router-link" :to="{path:'/'}">
              <img
                loading="lazy"
                src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
                alt="Lightweight UI components for Vue.js based on Bulma"
              />
            </b-navbar-item>
          </template>
          <template slot="start">
            <b-navbar-item href="#">Home</b-navbar-item>
            <b-navbar-item href="#">Services</b-navbar-item>
            <b-navbar-item href="#">testimonials</b-navbar-item>
            <b-navbar-item href="#">About</b-navbar-item>
          </template>
          <template slot="end">
            <b-navbar-item tag="div">
              <div class="buttons">
                <a class="button is-primary">
                  <strong>Sign up</strong>
                </a>
                <a class="button is-light">Log in</a>
              </div>
            </b-navbar-item>
          </template>
        </b-navbar>
      </div>
    </div>
    <div class="hero-body">
      <div class="container has-text-centered">
        <h1 class="title mb-6">Welcome To Our Studio</h1>
      </div>
    </div>
  </div>
</template>
 <style>
</style>
<style lang="scss" scoped>
.bg {
  display: block;
  position: relative;
  max-width: 100%;
  height: auto;
  background-image: url('../../assets/images/welcome.jpg');
  background-repeat: no-repeat;
  background-attachment: scroll;
  background-position: center;
  background-size: cover;
}
a {
  &.navbar-item {
    font-family: RobotoMono, sans-serif;
    font-weight: 300;
    @media (min-width: 769px) {
      font-weight: 600;
      color: #7957d5;
    }
  }
}
h1 {
  &.title {
    font-family: RobotoMono;
    font-size: 1rem;
    font-weight: 390;
    @media (min-width: 769px) {
      font-weight: 500;
      font-size: 2.5rem;
    }
  }
}
</style>
