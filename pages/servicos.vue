<template>
 <div>
    <div>
       <div class="container mx-auto">
           <h1 class="text-lg font-bold">Serviços</h1>

           <NuxtLink to="/servicos/desenvolvimento-de-sites">
               Desenvolvimento de sites
           </NuxtLink>

           <NuxtLink to="/servicos/marketing-digital">
               Marketing Digital
           </NuxtLink>

           <br/>
           <br/>

           <nuxt-child />
       </div>
    </div>
 </div>
 
</template>

<script>
export default {
    name: '',

    // middleware() {
    //     console.log('middleware default')
    // },

    data() {
        return {

        };
    }

}
</script>

<style>

</style>