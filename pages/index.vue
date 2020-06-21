<template>
  <section class="container">
    <div>
      <brenetic-logo/>
      <h1 class="title">
        brenetic
      </h1>
      <h2 class="subtitle">
      </h2>
      <div class="links">
        <a
          href="https://uk.linkedin.com/in/brenetic"
          target="_blank"
          class="button--green">LinkedIn</a>
        <a
          href="https://github.com/brenetic"
          target="_blank"
          class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
import BreneticLogo from '~/components/BreneticLogo.vue'

export default {
  components: {
    BreneticLogo
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
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  color: #35495e;
  letter-spacing: 1px;
  visibility: hidden;
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
</style>

