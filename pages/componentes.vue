<template>
    <div>
        <h2 class="tl-main">Componentes</h2>
        
    </div>
    <div class="flex justify-center items-center gap-10 py-8">
        <ImageCard
      v-for="(card) in cards"
      :imageSrc="card.imageSrc"
      :title="card.title"
      :route="card.route"
        />
  </div>
</template>

<script setup>
import { ref } from 'vue'
import ImageCard from '@/components/cards.vue'
import logoImage from '@/assets/img/logos.png'
import botonImage from '@/assets/img/boton.png'
import iconImage from '@/assets/img/iconos.png'

const cards = ref([
  {
    imageSrc: logoImage,
    title: 'Logotipo',
    route: '/compos/logo'
  },
  {
    imageSrc: botonImage,
    title: 'Botones',
    route: '/compos/boton'
  },
  {
    imageSrc: iconImage,
    title: 'Iconos y formas',
    route: '/compos/icon'
  }
])
</script>

<style scoped>


    p {
        margin: 20px 0;
    }
</style>