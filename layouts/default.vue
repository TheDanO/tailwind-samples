<template>
  <div>
    <TheToolbar></TheToolbar>
    <div class="bg-white pt-20">
      <nuxt />
    </div>
  </div>
</template>

<script>
import TheToolbar from '~/components/TheToolbar.vue'

export default {
  components: {
    TheToolbar
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
</style>
