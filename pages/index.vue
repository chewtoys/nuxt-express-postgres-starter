<template>
  <section class="container">
    <div>
      <logo />
      <h1 class="title">
        Nuxt Express Postgres Starter
      </h1>
      <h2 class="subtitle">
        A full-stack starter project with Nuxt, Express and Postgres
      </h2>
      <div class="links">
        <nuxt-link class="button is-medium is-light" to="/login">
          Login
        </nuxt-link>
        <nuxt-link class="button is-medium is-light" to="/signup">
          Signup
        </nuxt-link>
        <a
          href="https://github.com/HugoDF/nuxt-express-postgres-starter"
          target="_blank"
          class="button is-medium is-primary"
        >GitHub</a>
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

<style scoped>
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
</style>
