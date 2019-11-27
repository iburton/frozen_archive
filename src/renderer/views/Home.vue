<template>
  <div>
    <section class="hero is-dark is-bold">
      <div class="hero-body">
        <br />
        <div class="content has-text-centered">
          <h1 class="title is-4">
            Vue-Electron-Template
          </h1>
          <p class="subtitle is-6">
            The boilerplate for making electron applications using vue.js.
          </p>
          <RouterLink class="button is-info" to="about">
            <i class="material-icons">info</i>
            <span>About</span>
          </RouterLink>
          <RouterLink class="button is-info" to="help">
            <i class="material-icons">help</i>
            <span>Help</span>
          </RouterLink>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'Home',
})
</script>

<style>
.hero-body {
  height: 100vh;
}
</style>
