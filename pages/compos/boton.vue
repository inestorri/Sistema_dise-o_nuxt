<template>
    <mainContent 
      pageTitle="Botones"
      :images="[
      { src: '/boton2.png', description: 'Sistema de botones con sus diferentes variantes dependiendo de su uso: hay dos paletas de color diferenciadas.' },
      { src: '/boton1.png' }
        ]"
    newRoute="/componentes"
    />
  </template>
  
  <script setup>
  import mainContent from '~/components/mainContent.vue';
  </script>
  
  <style scoped>
</style>