


<script setup lang="ts">
const version = 2 + 1
</script>




<template>
  <NuxtTime 
    :datetime="Date.now()" 
    weekday="long"
    year="numeric"
    month="short"
    day="numeric"
    hour="numeric"
    minute="numeric"
    second="numeric"
    timeZoneName="short"
  />
</template>














<style scoped>
.hello {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 3rem;
  padding: 2rem;
}
</style>
