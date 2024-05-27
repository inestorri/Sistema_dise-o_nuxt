<template>
    <div>
        <h2 class="tl-main">Home</h2>
        <p class="parrafo">
        Sistema de rediseño de Onda Cero una cadena de radio española generalista
        y de ámbito social. En esta web se pueden explorar los diferentes estilos y 
        sistemas que componen el rediseño de la marca. Los valores que se han procurado
        perseguir han sido la simplicidad, rejuvenecimiento y dinamismo. </p>
    </div>
    <div class="flex flex-col justify-around items-center">
        <img src="/assets/img/indexlogo.png" alt="">
        <div class="px-4 py-2 font-medium text-2xl bg-emerald-500 text-white rounded-2xl shadow-sm hover:scale-125 ease-out duration-300">
            <NuxtLink to="/estilos"> Ver estilos </NuxtLink>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>

    h2 {
        margin-bottom: 20px;
    }

    p {
        margin: 20px 0;
    }
</style>

