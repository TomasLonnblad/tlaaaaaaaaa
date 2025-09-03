


<script setup lang="ts">
const version = 2 + 1
</script>



<template>
  <div class="hello">
    Hello Nuxt {{ version }} and Tomas with extended module!
  </div>
</template>




<template>
  <NuxtLink to="https://nuxtjs.org">
    Nuxt website
  </NuxtLink>
  <!-- <a href="https://nuxtjs.org" rel="noopener noreferrer">...</a> -->
</template>



<style scoped>
.hello {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 3rem;
  padding: 2rem;
}
</style>
