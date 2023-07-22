<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral />
    </div>
    <div class="column is-three-quarter">
      <TheFormulario />
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import BarraLateral from './components/BarraLateral.vue'
import TheFormulario from './components/TheFormulario.vue'

export default defineComponent({
  components: { BarraLateral, TheFormulario },
  name: 'App',
})
</script>

<style></style>
