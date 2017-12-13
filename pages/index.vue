<template>
  <section class="container">
    <div>
      <!-- <logo/> -->
      <h1 class="title">
        c7d5a6
      </h1>
      <h2 class="subtitle">
        personal page
      </h2>
      <div class="links">
        <!-- <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation</a> -->
        <!-- <a href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey">GitHub</a> -->
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
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
  background-image: url(/cat.png);
    background-repeat: no-repeat;
    background-position: center bottom;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #333333;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #484848;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
