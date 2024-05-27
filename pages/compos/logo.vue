<template>
    <mainContent 
      pageTitle="Logotipo"
      :images="[
      { src: '/logotipo1.png', description: 'Construído partiendo de la tipografía MuseoModerno.Se ha adaptao la letra d a una versalita para que tenga coherencia con el juego que se emplea en la identidad a partir de la forma del círculo.' },
      { src: '/logotipo2.png', description: 'Representación del area de seguridad del logotipo. Se ha tomado como referencia la media circunferencia de la letra o.' },
      { src: '/logotipo3.png', description: 'Versiones correctas del logotipo.' },
      { src: '/logotipo4.png', description: 'Aplicaciones posibles del logotipo aceptadas.' },
      { src: '/logotipo5.png', description: 'Variaciones incorrectas del logotipo.' },
      { src: '/logotipo6.png', description: 'Sello corporativo Onda Cero. Con este sello corporativo se unifica el logotipo de la marca con ese elemento protagonista de la nueva identidad de Ondacero, que le aporta toda la vida y relación con el sonido.' },
        ]"
    newRoute="/componentes"
    />
  </template>
  
  <script setup>
  import mainContent from '~/components/mainContent.vue';
  </script>
  
  <style scoped>
</style>