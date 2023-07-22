<template>
  <header>
    <h1>
      <img src="../assets/logo.png" alt="" />
    </h1>
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'BarraLateral',
})
</script>

<style scoped>
header {
  background-color: #0d3b66;
  height: 100vh;
  width: 100%;
}
@media only screen and (max-width: 768px) {
  header {
    height: auto;
    padding: 2.5rem;
  }
}
</style>
