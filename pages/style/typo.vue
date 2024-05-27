<template>
    <mainContent 
      pageTitle="Tipografías corporativas"
      :images="[
      { src: '/tipografias.png', description: 'Tipografía Plus Jakarta utilizada en todo el sistema con diferentes pesos de la misma. Se ha optado por esta debido a su apariencia geométrica y redonda acorde con la forma del logotipo. Además por su alta legibilidad.' },
        ]"
    newRoute="/estilos"
    />
  </template>
  
  <script setup>
  import mainContent from '~/components/mainContent.vue';
  </script>
  
  <style scoped>
</style>