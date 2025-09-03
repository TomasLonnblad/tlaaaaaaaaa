


<script setup lang="ts">
const version = 2 + 1
</script>





<template>
  <button @click="open = true">
    Open Modal
  </button>
  <Teleport to="#teleports">
    <div v-if="open" class="modal">
      <p>Hello from the modal!</p>
      <button @click="open = false">
        Close
      </button>
    </div>
  </Teleport>
</template>













<style scoped>
.hello {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 3rem;
  padding: 2rem;
}
</style>
