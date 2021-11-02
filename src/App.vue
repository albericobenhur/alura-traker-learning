<template>
  <main class="columns is-gapless is-multiline"></main>
  <div class="is-flex">
    <div class="column is-one-quarter">
      <BarraLateral />
    </div>

    <div class="column is-three-quarter">
      <Formulario />
      <!-- lista de tarefas ??-->
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import BarraLateral from "./components/BarraLateral.vue";
import Formulario from "./components/Formulario.vue";

export default defineComponent({
  name: "App",
  components: {
     BarraLateral,
     Formulario 
  }
});
</script>

<style>
</style>
