<template>
    <mainContent 
      pageTitle="Tratamiento fotográfico"
      :images="[
      { src: '/foto_hombre.png', description: 'Imagen de Carlos Alsina. Sobre icono de la variante del logo. ' },
      { src: '/foto_mujer.png', description: 'Imagen de Julia Otero. Sobre icono de la variante del logo.' }
        ]"
    newRoute="/estilos"
    />
  </template>
  
  <script setup>
  import mainContent from '~/components/mainContent.vue';
  </script>
  
  <style scoped>
</style>