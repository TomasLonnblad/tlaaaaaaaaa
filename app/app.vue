


<script setup lang="ts">
const version = 2 + 1
</script>



<template>
  <NuxtLink to="https://twitter.com/nuxt_js">
    Nuxt Twitter
  </NuxtLink>
  <!-- <a href="https://twitter.com/nuxt_js" rel="noopener noreferrer">...</a> -->

  <NuxtLink to="https://discord.nuxtjs.org" rel="noopener">
    Nuxt Discord
  </NuxtLink>
  <!-- <a href="https://discord.nuxtjs.org" rel="noopener">...</a> -->

  <NuxtLink to="/about" target="_blank">About page</NuxtLink>
  <!-- <a href="/about" target="_blank" rel="noopener noreferrer">...</a> -->
</template>


<style scoped>
.hello {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 3rem;
  padding: 2rem;
}
</style>
