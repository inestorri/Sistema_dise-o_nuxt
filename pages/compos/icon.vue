<template>
    <mainContent 
      pageTitle="Iconos y formas"
      :images="[
      { src: '/iconos.png', description: 'Iconos utilizados en la interfaz de la app. Recogen todas las utilidades y herramientas de la aplicación.' },
      { src: '/forma.png', description: 'La identidad de la marca se representa a través de la variabilidad y juego del círculo. Adopta diferentes formas para representar las funciones de la marca. Esto se aplica en el estilo fotográfico.' }
        ]"
    newRoute="/componentes"
    />
  </template>
  
  <script setup>
  import mainContent from '~/components/mainContent.vue';
  </script>
  
  <style scoped>
</style>