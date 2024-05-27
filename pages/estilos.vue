<template>
    <div>
        <h2 class="tl-main">Estilos</h2>
        
    </div>
    <div class="flex justify-center items-center gap-10 py-8">
        <ImageCard
      v-for="(card, index) in cards"
      :key="index"
      :imageSrc="card.imageSrc"
      :title="card.title"
      :route="card.route"
        />
  </div>
</template>

<script setup>
import { ref } from 'vue'
import ImageCard from '@/components/cards.vue'
import colorsImage from '@/assets/img/colors.png'
import typoImage from '@/assets/img/typo.png'
import fotoImage from '@/assets/img/foto.png'

const cards = ref([
  {
    imageSrc: colorsImage,
    title: 'Colores corporativos',
    route: '/style/colores'
  },
  {
    imageSrc: typoImage,
    title: 'Tipografías',
    route: '/style/typo'
  },
  {
    imageSrc: fotoImage,
    title: 'Fotografía',
    route: '/style/foto'
  }
])
</script>

<style scoped>
    h2 {
        margin-bottom: 20px;
    }

    p {
        margin: 20px 0;
    }
</style>