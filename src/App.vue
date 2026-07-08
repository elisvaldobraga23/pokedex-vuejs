<script setup>
  // importação dos elementos vue-routes
  import { RouterLink, RouterView } from 'vue-router'

  // Importação do Bootstrap
  import "bootstrap/dist/css/bootstrap.min.css"

  // Importar estilo CSS
  import "./complementos/estilos.css"

  // Importar componente de Navegação
  import BarraNavegacao from './components/BarraNavegacao.vue';

</script>

<template>
  <!-- Barra de Navegação -->
  <BarraNavegacao />

  <!-- Visualizar conteudos das páginas  -->
  <RouterView />
</template>

<style scoped>

</style>
