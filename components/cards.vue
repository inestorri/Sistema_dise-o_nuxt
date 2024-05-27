<template>
    
        <div class="max-w-sm rounded-xl overflow-hidden bg-white shadow-lg">
            <img class="w-full" :src="imageSrc" :alt="title" />
            <div class="px-6 py-4 bg-gray-100">
                <div class=" text-2xl mb-2">{{ title }}</div>
            </div>
        <div class="px-6 pt-4 pb-8 bg-gray-100">
            <nuxt-link :to="route" class="bg-emerald-500 hover:bg-emerald-700 text-white py-2 px-4 rounded-2xl ">
            Leer más
            </nuxt-link>
        </div>
    </div>
</template>
  
<script setup>
  const props = defineProps({
  imageSrc: {
    type: String,
    required: true
  },
  title: {
    type: String,
    required: true
  },
  route: {
    type: String,
    required: true
  }
})
</script>

<style scoped>

</style>

