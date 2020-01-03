<template>
  <div class="pt-10 mx-20">
    <div class="flex justify-center mb-10">
      <div class="inline-flex mx-auto">
        <nuxt-link
          tag="button"
          to="/oncourt"
          class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold py-2 px-4 rounded-l focus:outline-none"
        >
          Cards
        </nuxt-link>
        <nuxt-link
          tag="button"
          to="/oncourt/match"
          class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold py-2 px-4 rounded-r focus:outline-none"
        >
          Matches
        </nuxt-link>
      </div>
    </div>

    <div class="px-2">
      <NuxtChild></NuxtChild>
    </div>
  </div>
</template>

<style scoped>
.nuxt-link-exact-active {
  @apply bg-gray-400;
}
</style>
