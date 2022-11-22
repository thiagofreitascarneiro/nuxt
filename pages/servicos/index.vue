<template>
     <div>
    <div class="bg-gray-100">
        <div class="container mx-auto flex items-center space-x-4 h-10 mb-10">
            <NuxtLink to="/a-empresa">A empresa</NuxtLink>
            <NuxtLink to="/servicos">Serviços</NuxtLink>
            <NuxtLink to="/produtos">Produtos</NuxtLink>
        </div>

    </div>
  

    <div>
        <div class="container mx-auto">
            <h1 class="text-lg font-bold">Serviços</h1>

            <NuxtLink to="/servicos/desenvolvimento-de-sites">
                Desenvolvimento de sites
            </NuxtLink>

            <NuxtLink to="/servicos/marketing-digital">
                Marketing Digital
            </NuxtLink>

            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus tempore non accusamus, 
                ratione alias aliquam dicta assumenda aspernatur quasi fugiat corrupti eos dolorem sequi autem id! Doloribus odio labore nam!
            </p>
        </div>
    </div>
  </div>
  
</template>

<script>
export default {

}
</script>

<style>

</style>