<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container  mx-auto p-4 flex justify-between">
                <NuxtLink to="" class="flex items-center"><img src="/assets/img/logo.svg" class="h-full max-h-10" ></NuxtLink>
                <ul class="flex gap-8">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/estilos" class="">Estilos</NuxtLink></li>
                    <li><NuxtLink to="/componentes">Componentes</NuxtLink></li>
                </ul>
           
                
            </nav>
        </header>

        <div class="container mx-auto p-4">
            <slot />
        </div>
    </div>
</template>

<style scoped>
.router-link-exact-active {
        background-color: rgb(47, 172, 102);
        color: white;
        border-radius: 20px;
        padding: 8px
    }


</style>