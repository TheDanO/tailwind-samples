<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        tailwind-samples
      </h1>
      <h2 class="subtitle">
        Project for storing tailwind files
      </h2>
      <div class="mt-4">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="rounded p-3 mr-5 border border-green-700 text-green-600 hover:bg-green-600 hover:text-white"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="rounded p-3 px-6 border border-blue-900 text-blue-900 hover:bg-blue-900 hover:text-white"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
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
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
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
