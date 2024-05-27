<template>
    <mainContent 
      pageTitle="Colores corporativos"
      :images="[
      { src: '/color_primario.png', description: 'Colores principales de la marca. El logotipo se construye a partir de ellos.' },
      { src: '/color_secundario.png', description: 'Colores secundarios para hover y avisos en naranja complementario.' },
      { src: '/color_secundario2.png', description: 'Tema de la app en colores oscuros para cards y fondo.' },
      { src: '/color_secundario3.png', description: 'Temas claros para textos sobre los fondos oscuros.' }
        ]"
    newRoute="/estilos"
    />
  </template>
  
  <script setup>
  import mainContent from '~/components/mainContent.vue';
  </script>
  
  <style scoped>
</style>