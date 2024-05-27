<template>
   <div class="p-4">
     <NuxtLink :to="newRoute" class="mb-4 p-2 text-emerald-500 hover:text-emerald-700 inline-flex items-center">
      <ArrowLeftIcon class="h-5 w-5 mr-2" />
       Volver al menú anterior
     </NuxtLink>
     <h1 class="text-5xl font-bold mb-10">{{ pageTitle }}</h1>
      <div class="grid grid-cols-2 gap-6" v-if="images.length">
         <div v-for="(image, index) in images" :key="index" class="flex flex-col" >
            <img :src="image.src" alt="Imagen de la página" class="mb-2 w-full h-aut rounded-xl shadow-lg">
            <p class="mt-2 text-lg text-gray-400">{{ image.description }}</p>
         </div> 
      </div>
   </div>
 </template>
 
 <script setup>
 import { ArrowLeftIcon } from '@heroicons/vue/solid'
 const props = defineProps({
   pageTitle: {
     type: String,
     required: true
   },
   images: {
     type: Array,
     required: true,
     default: () => []
   },
   newRoute: {
     type: String,
     required: true
   }
 })

 </script>

 <style scoped>
</style>


 