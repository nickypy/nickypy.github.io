<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        nickypy
      </h1>
      <div class="links">
        <a
          href="https://github.com/nickypy"
          target="_blank"
          class="button"
        >
          🐙 GitHub
        </a>
        <a
          href="https://linkedin.com/in/nickpagsanjan"
          target="_blank"
          class="button"
        >
          💼 LinkedIn
        </a>
        <a
          href="https://soundcloud.com/nickypy"
          target="_blank"
          class="button"
        >
          🎸 Soundcloud
        </a>
        <a
          href="mailto:pagsanjan.nick@gmail.com"
          target="_blank"
          class="button"
        >
          💌 Email Me!
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Logo from '~/components/Logo.vue'

export default Vue.extend({
  components: {
    Logo
  }
})
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 42px;
  letter-spacing: 1px;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
