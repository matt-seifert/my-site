<template>
  <section class="container">
    <div>
      <!-- <app-logo/> -->
      <img class="matt-head" src="../assets/matt-head.jpg" aria-hidden="true" />
      <h1 class="title">Matt-Seifert.com is: </h1>
      <h2 class="subtitle">
        <vue-typed-js :strings="['Being worked on', 'Procrastinating', 'Coming soon...']" :typeSpeed="100">
          <span class="typing"></span>
        </vue-typed-js>
      </h2>
      <!-- <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
      </div> -->
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: linear-gradient(to bottom, #008CDC, #E3FFFE);
  background-attachment: fixed;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.matt-head{
  height: 300px;
}
</style>

